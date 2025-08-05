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
- Package Name Viewer apk
- [Download apk](https://play.google.com/store/apps/details?id=com.csdroid.pkg)
- [Termux](https://f-droid.org/en/packages/com.termux/)
- Root access inside Termux (`su` command must work)

---

## 🚀 Installation & Usage

1. Open Termux

2. Download the script:
  ```
    git clone https://github.com/King-Ali12/System-Apps-Delete.git
   ```

4. Give it permission to run:
```
    chmod +x uninstall.sh
```
5. Make sure you have root access:
   Run this command:-
  ```
    su
```
6. Run the script:
```
    ./uninstall.sh
```
## 📝 How It Works
* Download The Package name viewer apk from the playstore and install it after that open and search apk which you want uninstall 
* The script lists installed apps and lets you search by a keyword (e.g., "face").
* You choose which app to uninstall from the list.
* If successful, it logs the uninstalled app details (package name + APK path) to:

  ```
  /sdcard/AppBackup/uninstalled_apps.txt
  
**If You Want Restore Delete App Check uninstalled_apps.txt
Here Save All Deleted Apk Package Name Copy Package Name And 
Use Restore Apk Option
  ```

---
## 👑 Credits

* 💡 Script by: **KING-ALI**
* 🗨️ Telegram: [@KING_ALI12](https://t.me/KING_ALI12)

---
### 🧩 Step 1 - ***Launch the Tool**

![Step 1](images/1.png):
---

### 🔍 Step 2 - **Download Package Names Viewer **
Search Apk Which You Want Uninstall:

![Step 2](images/2.png):
---

### 🔍 Step 3 - Keywords Search
Package name like `org.lineageos.etar`
You type only **`line`, `etar`** — any two words or more, then press Enter:

![Step 3](images/3.png):

---
### 🗑️ Step 3 - **Select Apk and Uninstall**
Checked Carefully Package Name Which APK You Want to Uninstall:

![Step 4](images/4.png):

---

## ⚠️ Disclaimer

* ⚠️ **Use at your own risk**. Uninstalling essential system apps may break your device.
* 🛑 Always double-check before confirming an uninstallation.

---


 
