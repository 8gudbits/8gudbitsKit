# 8gudbitsKit

**8gudbitsKit is a collection of tools to perform various tasks including file encryption, process management, network related stuff and more. Whether you’re a developer, sysadmin, or just someone who loves tinkering with technology, these utilities can come in handy.**

## Getting Started 🚀

### Clone the Project

- To get started, 🔗 clone the project using Git:</li>
  ```bash
  git clone --depth 1 https://github.com/8gudbits/8gudbitsKit.git
  ```
- Or, you can download exe files for each tool individually by clicking **[here](./bin)** or directly by clicking on the app's name from the list below.

### Available Tools

#### [💾 ADSman v1.2](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/ADSman.exe)

- **Description:** Tool for managing alternate data streams in files on NTFS file systems. Click [here](https://github.com/8gudbits/ADSman) for more information about Alternate Data Streams (ADS).
- **Source code:** [ADSman Repository](https://github.com/8gudbits/ADSman)
- **Usage:**
  ```bash
  ADSman [--file/-f <file>] [--add/-a <source> --to/-t <target>] [[--remove/-rm | --extract/-e <adsName>] --from-file/-ff <filename>] [--nobanner/-n] [--help/-h]
  ```

#### [💾 HowFastIs v1.1](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/HowFastIs.exe)

- **Description:** A command-line utility to check how fast a program finishes executing.
- **Source code:** [HowFastIs Repository](https://github.com/8gudbits/HowFastIs)
- **Usage:**
  ```bash
  HowFastIs [--help/-h] [--nobanner/-n] [--file/-f <filename>]
  ```

#### [💾 IPof v1.0](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/IPof.exe)

- **Description:** Finds IPv4 and IPv6 addresses of any specified url.
- **Source code:** [IPof Repository](https://github.com/8gudbits/IPof)
- **Usage:**
  ```bash
  IPof --url/-u <url> [--nobanner/-n] [--help/-h]
  ```

#### [💾 LnkScout v1.1](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/LnkScout.exe)

- **Description:** A tool to scan directories for shortcut (`.lnk`) files, verifying their validity with options to display or remove invalid shortcuts.
- **Source code:** [LnkScout Repository](https://github.com/8gudbits/LnkScout)
- **Usage:**
  ```bash
  LnkScout <directory path> [--valid/-v | --invalid/-i [--remove/-r]] [--sort/-s] [--nobanner/-n] [--help/-h]
  ```

#### [💾 MyWiFiKey v1.0](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/MyWiFiKey.exe)

- **Description:** Displays the passwords of previously accessed WiFi networks, in case you need to share them and you don’t remember their password.
- **Source code:** [MyWiFiKey Repository](https://github.com/8gudbits/MyWiFiKey)
- **Usage:**
  ```bash
  MyWiFiKey [--nobanner/-n] [--help/-h]
  ```

#### [💾 Perks v1.1](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/Perks.exe)

- **Description:** CLI tool for generating and verifying file hashes (MD5, SHA1, SHA256, SHA512) across directories.
- **Source code:** [Perks Repository](https://github.com/8gudbits/Perks)
- **Usage:**
  ```bash
  Perks -[md5|sha1|sha256|sha512] [path] [-f/--file <file.perks>] [-l/--logfile <file.log>] [-n/--nobanner]
  Perks -v/--verify [path] [-f/--file <file.perks>] [-l/--logfile <file.log>] [-n/--nobanner]
  ```

#### [💾 Pidof v1.2](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/pidof.exe)

- **Description:** Tool to list the PIDs and memory usage of specified processes by their file names or window title.
- **Source code:** [Pidof Repository](https://github.com/8gudbits/Pidof)
- **Usage:**
  ```bash
  pidof [<filename>...[--title/-t <title>]] [--nobanner/-n] [--help/-h]
  ```

#### [💾 PulseNet v1.1](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/PulseNet.exe)

- **Description:** Tool to measure the peak download and upload speeds of your internet connection.
- **Source code:** [PulseNet Repository](https://github.com/8gudbits/PulseNet)
- **Usage:**
  ```bash
  PulseNet [--upload/-u] [--download/-d] [--nobanner/-n] [--help/-h]
  ```

#### [💾 RegiStart v1.0](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/RegiStart.exe)

- **Description:** CLI tool to manage Windows registry auto-start programs.
- **Source code:** [RegiStart Repository](https://github.com/8gudbits/RegiStart)
- **Usage:**
  ```bash
  RegiStart [--scan/-s] [--remove/-r] [--locations/-l] [--add/-a] [--nobanner/-n] [--help/-h]
  ```

#### [💾 SecurByte v1.1](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/SecurByte.exe)

- **Description:** Encrypts and decrypts any type of file with a password using AES-256-CBC algorithm.
- **Source code:** [SecurByte Repository](https://github.com/8gudbits/SecurByte)
- **Usage:**
  ```bash
  SecurByte [--encrypt-file/-ef | --decrypt-file/-df <filepath>] [--passwd/-p <password>] [--nobanner/-n] [--help/-h]
  ```

#### [💾 UnRecover v2.0](https://github.com/8gudbits/8gudbitsKit/raw/main/bin/UnRecover.exe)

- **Description:** Securely overwrite's sensitive files and clean free space of previously deleted files.
- **Source code:** [UnRecover Repository](https://github.com/8gudbits/UnRecover)
- **Usage:**
  ```bash
  UnRecover <drive letter> [--pass/-p <number>] [--suppress-warning/-s] [--nobanner] [--help/-h]
  ```

---

## Contributing

Contributions are welcome! If you have an idea for a new tool or want to improve an existing one, feel free to submit a pull request.

## License

This project is licensed under the **[Apache License 2.0](https://github.com/8gudbits/8gudbitsKit/blob/main/LICENSE)** - see the LICENSE file for details.

---

<p align="center">More Tools Comming Soon . . .</p>

