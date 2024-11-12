# MorphleLabTest

<h2 style="color:blue;">Welcome to the System Information Page!</h2>


## Project Description
This Django application provides a simple /htop endpoint that, when accessed, displays:

Name: Hardcoded to the developer's name (Abhijeet Aayush).
System Username: Obtained from the system environment.
Server Time (IST): Current server time in IST.
Top Output: Output of the top command, which displays system resource usage.
This can be useful for quickly monitoring system information on a web interface.

## 🌟 Features

- **System Information** 📊
- **IST Time Zone Support** 🌐
- **Real-time Resource Monitoring** 🚀

## Technologies Used
Django: Web framework for building and serving the application.
Python: Core programming language for the application logic.
Subprocess: To retrieve the system's top command output.
pytz: For timezone management, specifically to display IST.

## 🛠️ Setup Instructions

### Prerequisites
- Python 3.x
- `pip` package manager

```bash
# Clone the repository
git clone https://github.com/AbhijeetAayush/MorphleLabTest.git

# Navigate to the project directory
cd MorphleLabTest

# Install dependencies
pip install -r requirements.txt
