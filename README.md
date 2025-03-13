# Project: Secure Authentication Using User Certificates

## Overview
This project implements a secure authentication protocol where a certificate is issued to each user during the sign-up process. The user then uses this certificate to authenticate themselves to the website, ensuring secure communication and verification.

## Problem Statement
In the current protocol, while no attacks were detected, the user and the website are not properly authenticating each other. This creates a potential security risk where a user may not be properly verified by the website.

## Solution
To solve this issue, we generate a unique certificate for each user during the sign-up process. This certificate is used by the user to authenticate themselves to the website. Although the website does not have its own certificate, the user’s certificate allows the website to verify the legitimacy of the user. This enhances the security and trust between the user and the website.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/VasudevGoud/Port_Scan.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Port_Scan
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the `portscan.py` script (if applicable):
   ```bash
   python portscan.py
   ```
2. Follow the authentication flow using the user-issued certificate.
3. Ensure secure communication is established between the user and the website.

## Contributing
Feel free to contribute by submitting issues and pull requests. Please follow best coding practices and security standards.


