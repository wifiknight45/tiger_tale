# tiger_tale
quasi-silent_listener
# Stealth Port Scanner

This repository contains a Python script for performing stealthy port scans on target systems. 

## Disclaimer

**Important:** This tool is for educational and ethical security testing purposes only. It should only be used on systems or networks where you have explicit permission from the owner or administrator. Unauthorized port scanning is illegal and can have serious consequences. The author of this code is not responsible for any misuse or damage caused by this script.

## Features

* **Stealthy Scanning:** Uses randomized timing, randomized source ports, and limited threading to avoid detection by intrusion detection systems.
* **Service Identification:** Attempts to identify the services running on open ports using a dictionary of common ports and their services.
* **CSV Output:** Saves scan results to a CSV file for easy analysis.
* **Thread-based:** Utilizes threading for faster scanning of multiple ports.
* **Error Handling:** Includes error handling for hostname resolution and socket errors
## Requirements

* Python 3.x
* Libraries: `socket`, `threading`, `queue`, `time`, `csv`, `random`, `ssl`, `datetime` (These are usually included with Python)

## Usage

1. **Clone the repository:**
2. **Change target host:**
    * Open `stealth_port_scanner.py` and modify the `target_host` variable in the `if __name__ == "__main__":` block to the target you have permission to scan:
3. **Run the script:**
4. ## Output

The script will print the scan progress and results to the console. It will also save the results to a CSV file named `tiger_tale_[timestamp].csv` in the same directory.

## Contributing

Contributions are welcome! Please feel free to submit pull requests for bug fixes, improvements, or new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* Inspired by various online resources on port scanning and network security. This code was generated using AGI for the purposes of learning how to code in Python and  Please use responsibly, only on networks that you have permission to scan. It is highly recommended to run this script in a virtual/sandbox environment before actually utilizing on a live network. 
