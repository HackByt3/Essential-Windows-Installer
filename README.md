<p align="center">
  <img src="https://github.com/HackByt3/Essential-Windows-Installer/blob/main/EssentialInstallerBanner_Final.png?raw=true" alt="Essential Windows Installer Banner" width="100%">
</p>


# 🛠 Essential Windows Installer

A portable, menu-driven command-line installer for fresh Windows installs. Just plug in your USB, run the script, and select what apps you want to install.

---

## 🔧 Features

- Interactive terminal menu (Batch)
- Install essential apps individually or all at once
- Runs fully offline (uses local installers)
- Organized and expandable folder structure

---

## 📦 Included Installers (Placeholders)

| Category     | Tools                     |
|--------------|----------------------------|
| Browsers     | Chrome, Firefox           |
| Utilities    | 7-Zip, VLC, Notepad++     |
| Security     | Malwarebytes              |
| Runtimes     | Visual C++ Redistrib, .NET|
| Office       | LibreOffice               |
| Drivers      | Snappy Driver Installer   |

---

## 🚀 Usage

1. Plug USB into Windows
2. Run `Scripts/installer.bat` as Administrator
3. Choose what to install from the menu

---

## 📂 Folder Structure

Essential-Windows-Installer/
├── Scripts/
│ └── installer.bat
├── SoftwareInstallers/
│ └── [Organized Installers by Category]

********
---


## 🎙️ Why I Built This

Every time I set up a fresh Windows machine, I found myself repeating the same steps — download a browser, install 7-Zip, update drivers, run security tools... and it was even worse without internet.

I wanted something:
- Fast and portable
- Fully offline
- Customizable and clean

So I built this terminal-based USB installer to streamline the whole process. Whether you're rebuilding PCs, helping friends, or doing IT work, this tool saves time and effort.

It's open source, so feel free to fork it, tweak it, or contribute!

---

## 🔄 Future Plans

- PowerShell version
- Install logging
- GUI front-end (Optional)
- Auto-check if apps are already installed

---

## 💡 Contributions

Pull requests and ideas welcome!

---

## 📜 License

MIT
