# Privacy Policy for Robo NP Notinhas

**1. Data Collection and Storage**
Robo NP Notinhas is a standalone desktop application. All personal data, including credentials (CPFs, passwords) and tax document hashes, are encrypted locally using AES-256 (Fernet) and stored strictly on the user's machine (`%APPDATA%/RoboNP`). 

**2. Data Transmission**
The application does not transmit any personal data, credentials, or tax information to third-party servers or the developer's servers. The software only communicates directly with the official Nota Paraná portal to perform the user-requested automation.

**3. Telemetry and Updates**
The application connects to the GitHub API exclusively to check for version updates and securely download release binaries. In the event of a critical system crash, anonymized error logs (stack traces without user data) may be generated locally and sent to the developer for debugging purposes.

**4. Third-Party Services**
The application downloads the necessary Chromium WebDriver via `webdriver-manager` from official Google repositories.
