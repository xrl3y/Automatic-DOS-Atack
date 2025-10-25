# Automatic-DOS Atack
This Bash script performs a Denial of Service (DoS) attack by sending a flood of packets to a specified target IP address or domain. Users can specify the target's port, the type of attack (SYN, UDP, ICMP, or a combination), and the interval between packets.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8e6f1430-3a65-4da2-a2c7-1a9bdbc748f1" alt="image" />
</p>




# DoS Attack Script

## Overview

This Bash script allows users to perform Denial of Service (DoS) attacks by sending a flood of packets to a specified target IP address or domain. The script is designed for educational and testing purposes only. Use it responsibly and only on systems you own or have explicit permission to test.

## Features

- **Flexible Targeting**: Specify either an IP address or a domain name.
- **Multiple Attack Types**: Choose between SYN, UDP, ICMP, or a combination of all.
- **Customizable Parameters**: Set the target port and the interval between packets.
- **Error Handling**: Validates input parameters to ensure correct usage.
- **User-Friendly Help**: Displays usage instructions and options when requested.

## Requirements

- **hping3**: This tool is required for generating packets. Install it using the following command:
  ```bash
  sudo apt-get install hping3
  ```

<p align="center">
  <img src="https://github.com/user-attachments/assets/574f68ae-f6d6-458c-967d-6c61e0aa8a71" alt="image" />
</p>


  
Usage
To use the script, follow these steps:

Clone the repository:

```bash
git clone https://github.com/xrl3y/Automatic-DOS.git
cd Automatic-DOS
```
Make the script executable:

```bash
chmod +x DOS.sh
```
Run the script with the desired options:

```bash
./DOS.sh -i <target_ip_or_domain> -p <port> -t <attack_type> -I <interval>
```
Example:

```bash
./DOS -i example.com -p 80 -t syn -I 1000
```

Options:

- i <IP_address_or_domain>: Specify the target IP address or domain name.

- p <port>: Specify the target port (default is 80).

- t <type>: Specify the type of attack (syn, udp, icmp, or all).

- I <interval>: Specify the interval between packets in microseconds (optional).

- h: Display help information.

# Disclaimer 🛑

⚠️ **Warning:** This content is for educational purposes only.

This repository and its contents are provided for educational, research, and learning purposes only.

- The material shown — including scripts, commands, and examples — is intended to demonstrate concepts and techniques in a controlled and authorized environment.

- Do not use this material to perform illegal, unauthorized, or harmful activities against networks, systems, or people.

The author accepts no responsibility for any damage, loss, misuse, unauthorized access, legal consequences, or incidents that result from the use of this content. By using this material you agree that you do so at your own risk and that you have the necessary permissions to test or run the procedures described here.

- If you plan to practice on a network or device you do not own, obtain explicit written permission from the owner before proceeding.

## Recommendations

- Use isolated lab environments (virtual machines, test networks) for experimentation.

- Respect applicable laws and your organization’s policies.

- If you have legal or ethical doubts, consult a qualified professional.


---

## Author

This project was developed by **xrl3y**.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">


## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

WARNING: This script is intended for educational and research purposes only. Performing a DoS attack on networks or servers without explicit permission is illegal and unethical. Always ensure that you have authorization before testing any system.

Author: xrl3y
