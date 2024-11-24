# PingGU
## Project Overview
PingGU  is designed to facilitate the collection of system information and memory dumps from a target device to a host PC. The target device connects to a Flask web server running on the host PC. Upon pressing a button in the web interface, the target device sends detailed system information, including the list of running processes and memory usage statistics, to the host.

### Features
- **Flask Web Interface**: A web interface hosted on the target device that allows the user to interact with the system and send memory dumps to the host PC.
- **System Information**: Collects system information like platform details, memory usage, CPU info, disk usage, and a list of running processes.
- **Memory Dump**: When a button is clicked on the target device's interface, the system gathers detailed memory dump data and sends it to the host PC.

## Project Status
PinGU is **still in the works**. Currently, it is functional for sending basic system information from the target device to the host PC. The memory dump feature is under development and may be subject to changes or improvements in the future.

## Getting Started
### Requirements
- Python 3.x
- Flask (`pip install flask`)
- psutil (`pip install psutil`)

### Installation
- Download the project file
- When downloaded, Ensure you have all the libs downloaded.
- Open Visual Basic (or any other code editors) and run
- It should start running automatically.
