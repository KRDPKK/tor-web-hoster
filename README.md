# ONIONHOST

ONIONHOST is a Windows Forms app to host Tor hidden services easily on your machine. It downloads and runs Tor, manages onion addresses, and lets you pick service templates.

## Features

- Auto-download and setup of Tor
- Start/stop Tor hidden services with onion address display
- Tabbed UI with service template selection
- Templates include:
  - Anonymous Chat System
  - Anonymous File Sharing Platform

## Usage

1. Start the app.
2. In **Tor Status** tab, click **Start Hosting** to launch Tor and create a hidden service.
3. The onion address will show when ready.
4. Switch to **Templates** tab to select a service template.
5. Click **Deploy Template** to get instructions.

> **Note:** The templates are stubs. Please use your own Python Flask templates (like `chat.py` or `fileshare.py`) and run them manually on `127.0.0.1:8080` to test with the hidden service.

## Requirements

- Windows 8 or later
- Internet for downloading Tor initially
- Python Flask environment for running templates

---

Happy onion hosting!
