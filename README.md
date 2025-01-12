# PortScannerPY
A port scanner in Python. This script scans a specified IP address for open ports within a range.

## Features
- Scans all 65,535 ports of a given IP address.
- Identifies open ports and displays them.
- Simple and beginner-friendly code.

## Requirements
- Python 3.x

## Installation
1. Clone the repository:

   git clone https://github.com/yourusername/port-scanner.git

3. 	Navigate to the project directory:

	  cd port-scanner

### Usage

1.- Run the script:

	python port_scanner.py


2.- Enter the IP address you want to scan when prompted:

	Introduzca la dirección IP a escanear: 192.168.1.1

3.- The script will scan all ports and display whether each port is open or closed:

	Puerto Abierto: 80
	Puerto Cerrado: 81
	...
	
###Example Output

	Introduzca la dirección IP a escanear: 192.168.1.1
	Puerto Abierto: 22
	Puerto Cerrado: 23
	Puerto Cerrado: 24
	Puerto Abierto: 80

# Important Notes
**Use responsibly:** This tool is intended for educational purposes and testing authorized systems only. Scanning unauthorized systems without permission is illegal and may result in severe consequences.

The script has a timeout of 5 seconds per port, which may affect the total scanning time.
