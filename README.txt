$ sudo ss -tlnp     #lists all the open network ports on your server, along with the process ID (PID) and name of the program that is listening on each port. You can look for entries with the "State" column set to "LISTEN", which means that a program is actively waiting for incoming connections on that port.

