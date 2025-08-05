# 🚀 System Apps Uninstaller for Android (Termux)

A simple yet powerful Bash script that helps you **search**, **select**, and **uninstall system apps** directly from Termux with root access.

> 🔥 Created by **KING-ALI**  
> 📢 Join Telegram: [@KING_ALI12](https://t.me/KING_ALI12)

---

## 📦 Features

- 🔍 Search system apps by name (partial match supported)
- ✅ Uninstall selected apps with confirmation
- 🧾 Automatically logs all uninstalled apps to a backup file
- 📁 Backup log stored in `/sdcard/AppBackup/uninstalled_apps.txt`
- 🎨 Beautiful colored terminal UI for easy navigation

---

## ⚙️ Requirements

- Android phone rooted
- [Termux](https://f-droid.org/en/packages/com.termux/)
- Root access inside Termux (`su` command must work)

---

## 🚀 Installation & Usage

1. Open Termux

2. Download the script:

      git clone https://github.com/King-Ali12/System-Apps-Delete.git

3. Give it permission to run:

   chmod +x uninstall.sh

4. Make sure you have root access:
   Run this command:-
  
   su

6. Run the script:

    ./uninstall.sh

## 📝 How It Works

* The script lists installed apps and lets you search by a keyword (e.g., "face").
* You choose which app to uninstall from the list.
* If successful, it logs the uninstalled app details (package name + APK path) to:

  ```
  /sdcard/AppBackup/uninstalled_apps.txt
  ```

---

## ⚠️ Disclaimer

* ⚠️ **Use at your own risk**. Uninstalling essential system apps may break your device.
* 🛑 Always double-check before confirming an uninstallation.

---

## 👑 Credits

* 💡 Script by: **KING-ALI**
* 🗨️ Telegram: [@KING_ALI12](https://t.me/KING_ALI12)

---

## 📸 Screenshot (Optional)

> *(You can add a screenshot of the script in action for more impact)*

---

## 📜 License
