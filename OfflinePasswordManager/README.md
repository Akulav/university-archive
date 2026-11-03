# SeePass: Offline Password Manager

A secure password manager written in C# (WinForms) that works completely offline.

## Features

- Encrypted data storage and secure data erasure
- Encryption keys derived from username, password and PIM, which are never stored
- Import and export of data
- Read-only file attributes to protect data from corruption or accidental changes
- No logs or telemetry
- Light and dark modes
- Low system requirements

## Structure

| Folder | Description |
| --- | --- |
| `PasswordManager` | The main SeePass application |
| `SeePassInstaller` | A small installer that unpacks the application |

## Running

- **From a release:** download the latest release, extract all files, and keep the `.dll` files in the same folder as the executable.
- **From source:** open `PasswordManager/PasswordManager.sln` in Visual Studio, restore NuGet packages and press **Start**.

## Planned (never finished)

- Update checker
- Changing username, password or PIM
- Lower memory usage

See `TODO.txt` and `UPCOMING.md` for more notes.

## Credits

Icons by [Freepik](https://www.flaticon.com/authors/freepik) from [Flaticon](https://www.flaticon.com/).
