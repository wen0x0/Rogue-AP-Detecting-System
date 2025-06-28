# Rogue Access Point Detection System

This project implements a **Rogue Access Point Detection System** to identify and mitigate rogue APs in a local network, helping prevent **Evil Twin attacks**.

## Features

- Real-time monitoring of nearby wireless networks
- Detection of rogue access points attempting to impersonate legitimate APs
- Logging of suspicious AP details
- Automated alerting to notify security teams of detected threats

## Tools & Technologies

- **Kismet API** for real-time monitoring and data extraction
- **Airodump-ng** for wireless network scanning
- **Wifipumpkin** for simulating Evil Twin attacks during testing
- **Python** for integration, logging, and automation scripts

## Responsibilities

- Simulated rogue AP attacks to test detection accuracy
- Integrated Kismet API for continuous monitoring
- Implemented logging system for detected rogue APs
- Automated alerting mechanism for immediate notifications

## Usage

1. **Install dependencies**

   Ensure you have Kismet, Airodump-ng, Telegram, and Wifipumpkin installed on your system.

2. **Run Kismet server**

   ```bash
   sudo kismet
   ```
   
3. **Execute detection script**
  
  ```bash
  python detect_rogue_ap.py
  ```

4. **Monitor logs**
   
  Check the generated logs or configured alert channels for detection reports.


## Disclaimer

This project is intended for educational and defensive security purposes only. Unauthorized scanning or attack simulation on networks you do not own is illegal.


## License

This project is licensed under the MIT License.

---
