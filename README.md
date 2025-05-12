# Gmail Reverifier

A Node.js script to automate the process of re-verifying Gmail credentials using a combination of email, password, and recovery information. This tool is intended for educational or account management purposes **only**.

---

## 🚨 Disclaimer

This tool is intended **only for authorized use**. Do **not** use it on accounts you do not own or have explicit permission to access. Misuse of this tool may violate Gmail's Terms of Service and applicable laws. The author takes no responsibility for any misuse.

---

## 📁 File Structure

- `mail.js` – Main script that handles the re-verification process.
- `email.txt` – A list of Gmail addresses to verify.
- `password.txt` – Corresponding passwords, one per line.
- `recovery.txt` – Recovery emails or backup methods.

Ensure all files have the **same number of lines** and are **properly aligned** by index (line 1 in all three files corresponds to one account).

---

## 🚀 Setup & Usage

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- Internet connection.

### Installation

1. Clone the repository or download the files.
2. Install any dependencies (if required by `mail.js`):

   ```bash
   npm install

# Run the script

1. node mail.js

Make sure email.txt, password.txt, and recovery.txt are present in the same directory as mail.js.

📌 Notes
The script likely uses automation or API interaction, so ensure your IP is not blocked by Google for repeated attempts.

Consider rate limiting or using proxies if you are handling many accounts.
