# 🔐 KeePassXC — Secure Password Manager

**KeePassXC** is a cross-platform, open-source password manager. It allows you to securely store passwords, login credentials, PINs, 2FA keys, and other sensitive information in a locally encrypted database. A powerful utility for sysadmins, developers, DevOps, and privacy-focused users.

---

## ✅ Features

- Local, encrypted database (AES-256)
- Auto-fill credentials in browsers and applications
- Built-in password generator
- Support for YubiKey, SSH agent, and auto-lock
- Cross-platform: Linux, Windows, macOS
- Compatible with KeePass format (kdbx)

---

## 🔧 Installation

### Debian/Ubuntu
```bash
sudo apt install keepassxc
```

### Arch Linux
```bash
sudo pacman -S keepassxc
```

### Fedora
```bash
sudo dnf install keepassxc
```

### macOS (Homebrew)
```bash
brew install keepassxc
```

---

## 🚀 Basic Usage

### Create a New Database
1. Open KeePassXC
2. Go to **Database → New Database**
3. Set a **strong master password**
4. Save the database as a `.kdbx` file

### Add a New Entry
- Click **"Add new entry"**
- Enter name, username, password
- Optionally add a URL, notes, or a TOTP key for 2FA

### Use Browser Auto-Fill
- Install the **KeePassXC-Browser** extension (Chrome/Firefox)
- Enable integration via **Tools → Settings → Browser Integration**

---

## 🧩 Tips

- Enable auto-lock on inactivity for extra security
- Store your database file in an encrypted volume or sync it via Syncthing/Nextcloud
- Use a key file or YubiKey for two-factor unlock
- Make regular backups of your `.kdbx` file

---

## 📚 More Info

- Official site: [https://keepassxc.org](https://keepassxc.org)
- Documentation: [https://keepassxc.org/docs/](https://keepassxc.org/docs/)
- GitHub: [https://github.com/keepassxreboot/keepassxc](https://github.com/keepassxreboot/keepassxc)
