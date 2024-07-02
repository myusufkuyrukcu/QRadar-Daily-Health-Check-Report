# QRadar-Daily-Health-Check-Report

This QRadar Daily Health Check extension generates a comprehensive four-part report:
1) Top Log Sources: Displays the top 10 log sources over the last 24 hours in a time graph.
2) Event Rate (EPS): Shows the EPS (Events Per Second) graph based on EC over the last 24 hours in a time graph.
3) System Notifications: Displays notifications seen on the QRadar dashboard from the last 24 hours, sorted by the most recent to the oldest, including magnitude information.
4) Health Summary: Provides data from the last few minutes, including DiskUsage (if greater than 70%), IdleCpu (%), NumCpu (count), LoadAvg5, and SystemMemoryUsed (%).

Thanks to the saved searches (their names start with "DHC:"), you can run these queries manually.

Installation: DailyHealthCheck-*.zip file is imported from the QRadar GUI (Admin tab > Extensions Management > Add & Upload & Install)

Tested on QRadar v7.5.0 UP4+

Sample output: Daily Health Check.pdf
