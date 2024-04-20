<h2>By GabriMx7</h2>
App do canal By Gabrimx7

<p align="center">
<img src="core/logo.png" alt="Dark-Phish Logo"/>

<h1 align="center"> v2.2</h1>

**Dark-Phish** is a specialized phishing tool created for educational and security testing purposes. It provides users with the capability to simulate phishing attacks, enabling the assessment of system vulnerabilities and user awareness.


## Features

- **Multiple Tunneling Options**: Choose from various methods for flexible phishing simulation.

- **Auto-saved Credentials**: Victim credentials are stored automatically.

- **Credential Management**: Easily access and manage saved credentials.

- **Custom Phishing Templates**: Create customized and convincing phishing scenarios.

- **OTP Capture**: Efficiently collect one-time passwords for improved assessment capabilities.

- **URL Obfuscation:** Dark-Phish conceals phishing URLs, making them appear trustworthy and less suspicious.



## Tested on
- Kali Linux
- Termux

## Installation

```bash
apt install python3 curl php git openssh nodejs npm -y
```
```bash
pip3 install requests wget pyshorteners
```
```bash
git clone https://github.com/Cyber-Anonymous/Dark-Phish.git
cd Dark-Phish
```

## Usage 
*Before using Dark-Phish, ensure you have the necessary packages installed as mentioned in the installation section.*

- Run Dark-Phish
```bash
python3 dark-phish.py
```
- For help and usage information
```bash
python3 dark-phish.py -h
```
- To access saved credentials
```bash
python3 dark-phish.py -r
