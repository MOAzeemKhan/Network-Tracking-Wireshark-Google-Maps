# Network Traffic Visualization with Wireshark and Google Maps

This repository contains the code for a network traffic visualization project that utilizes the Python programming language, Wireshark, and Google Maps. The project takes a file of network traffic and converts it into a visual presentation using Google Maps.

## Getting Started
To use this code, you will need to have Python, Wireshark, and the Google Maps API installed on your system.

You will also need a file of network traffic data in the PCAP format, which can be captured using Wireshark.

## Running the Code
1. Clone or download the repository to your local system.

2. Open the file 'main.py' in your preferred Python IDE or text editor.

3. Replace the value of the 'ip' variable with the IP address of your choice.

4. Replace the value of the 'f' variable with the path to your PCAP file.

5. Run the code by executing the main() function.

The code will output the KML document that can be used to visualize the network traffic data on Google Maps.

## Dependencies
[dpkt](https://github.com/kbandla/dpkt)

[pygeoip](https://pypi.org/project/pygeoip/)

[socket](https://docs.python.org/3/library)


