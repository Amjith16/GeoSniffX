# Geosniff-X:Network Packet Analyzer

## Description
The Network Packet Analyzer is a Python application with a graphical user interface (GUI) built using PyQt. It provides powerful capabilities for capturing, analyzing, and visualizing network traffic. Users can capture packets from network interfaces or load pre-recorded PCAP files, view packet details such as IP addresses, port numbers, and protocols, and apply filters to focus on specific types of packets. The application supports common file operations for managing captured data and includes a unique feature to convert captured traffic into KML format for visualization on mapping software.

## Features
- Capture packets from network interfaces.
- Load pre-recorded PCAP files for analysis.
- View packet details, including IP addresses, port numbers, and protocols.
- Apply filters to focus on specific types of packets.
- Convert captured traffic into KML format for visualization on mapping software.
- Analyze packet details through interactive dialogs.

## Installation
1. Clone the repository to your local machine.
2. Install the required dependencies using `startup.sh'file.
3. Run the application using python3 main.py.

##startup.sh 
- chmod +x startup.sh: Providing permission to the file to execute 
- ./startup.sh: to run the file

## Usage
1. Start the application by running main.py.
2. Use the GUI to capture packets, load PCAP files, or apply filters.
3. Analyze packet details by selecting individual packets and opening the packet analyzer dialog.
4. Save captured packets or export them in PCAP format.
5. Convert captured traffic to KML format for visualization on mapping software.

## Requirements
- Python 3.x
- PyQt5
- dpkt
- IP2Location (for KML conversion)

## IP2Location database
To enable the KML conversion feature, you will need the IP2Location database. You can download the IP2Location Lite version database from [here](https://lite.ip2location.com/database/ip-country-region-city-latitude-longitude-zipcode-timezone).
Once downloaded, place the database file (IP2LOCATION-LITE-DB11.BIN) in the appropriate directory and ensure that the application can access it for KML conversion.

- Remember to change the path to the IP2Location Database in the function converttoKML

## Contributing
Contributions to the Network Packet Analyzer project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Special thanks to the developers of PyQt, dpkt, and IP2Location for their invaluable contributions to this project.
