# ISS-Overhead-notifier
International Space Station Notifier

This application tracks where the iSS is currently in the sky. 
When the ISS is in the night sky, right above where we are, then we send ourselves an email telling us to look up ans spot the fast-moving ISS.

-Data stored is in JSON form through JSON Viewer
-Libraries used - request, smtplib, time, datetime
-Raises an exception whenever there is status code
-To see what longitute and latitude is on the world map, we use tool called LatLong.net
-sunrise & sunset API to see when it is dark
-program will sleep for 60 sec and then run again
