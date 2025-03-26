# Noir

Permanent HWID spoofer written in C# (.NET)

![](https://github.com/user-attachments/assets/5a3efbee-27eb-4140-8eb9-4f940509f4d0)

## Features

- Not tested (it probably doesn't even work but whatever)
- Should (in theory) work on most games without anti-cheats that check TPM
- More of a wrapper, since nothing low-level is done
- Simple and clean console UI/UX
- Licensing system base + local encrypted keystore
- Spoofs/modifies SMBIOS tables, disk drive IDs, MAC addresses, and cleans USB registry permissions with motherboard brand fallbacks
- Built-in Windows Defender checks
- Built-in temp spoofer wrapper (cleaner + random temp spoof driver) + [tpm-spoofer](https://github.com/SamuelTulach/tpm-spoofer) integration
- Built-in serial checker (exports current serials to a `.txt` file and opens it in Notepad)

## Build

You need VS 2022 and the .NET Framework SDK.

1. Clone and open the solution (`noir.sln`) in Visual Studio
2. Modify the licensing system or add a bypass in `licensing.cs`
3. Click Build. Find the binary yourself.

## License

[MIT](LICENSE)
