Visual Monitoring of WinCC 7.5 Server Redundancy Status

In redundant WinCC systems, two servers ensure system fault tolerance.
However, the presence of redundancy does not guarantee that both servers are constantly in a healthy state.
For instance, one server might fail while the other continues to operate normally. An operator might not notice this, even though the system is running without redundancy.
WinCC provides internal system tags that allow for determining server status, roles, and synchronization states; however, constantly checking these tags via diagnostic lists is inconvenient.
To address this, a dedicated diagnostic display was developed to consolidate key redundancy parameters into a single window.

The screen displays:

*the status of both servers

*the current server roles

*communication status

*synchronization status

This enables a quick assessment of whether redundancy is truly operational, eliminating the need to search for information across individual system tags.
The solution is primarily intended for existing WinCC/PCS 7 systems where such a diagnostic screen was not originally included.
In some WinCC projects, this information is already displayed via standard or automatically generated tools.
The redundancy system itself remains unchanged; the solution utilizes existing internal WinCC tags, while the newly developed screen offers a more convenient way to monitor their status.
