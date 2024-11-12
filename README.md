# MorphleLabTest

#Project Description
This Django application provides a simple /htop endpoint that, when accessed, displays:

Name: Hardcoded to the developer's name (Abhijeet Aayush).
System Username: Obtained from the system environment.
Server Time (IST): Current server time in IST.
Top Output: Output of the top command, which displays system resource usage.
This can be useful for quickly monitoring system information on a web interface.

#Features
Displays system information via the /htop endpoint.
Real-time server time in Indian Standard Time (IST).
Resource usage stats from the top command.

#Technologies Used
Django: Web framework for building and serving the application.
Python: Core programming language for the application logic.
Subprocess: To retrieve the system's top command output.
pytz: For timezone management, specifically to display IST.
