# 🚚 ssd-dispatch-tracker - Track Dispatches in Real Time

[![Download ssd-dispatch-tracker](https://img.shields.io/badge/Download-ssd--dispatch--tracker-blue?style=for-the-badge)](https://github.com/Sequen0/ssd-dispatch-tracker/releases)

---

## 📘 What is ssd-dispatch-tracker?

ssd-dispatch-tracker is a desktop application designed to help logistics facilities manage their daily dispatch operations. It runs on Windows and provides a clear view of driver assignments and package tracking in real time. 

The app uses a simple interface with PyQt5, stores data locally with SQLite, and helps you manage driver badges and import package data quickly using CSV files.

It works well for busy warehouses handling over 100 drivers and thousands of packages every day.

---

## 💻 System Requirements

Before downloading, make sure your PC meets these needs:

- Windows 10 or newer (64-bit preferred)  
- 2 GB of free disk space  
- 4 GB RAM or more  
- Internet connection (for downloading and updates)  
- Basic Mouse and Keyboard  

The app runs offline once installed. It uses a local database to keep your data safe.

---

## 🚀 Getting Started

Follow these steps to get ssd-dispatch-tracker on your Windows PC.

### 1. Download the Installer

Click the button below to open the downloads page:

[![Download ssd-dispatch-tracker](https://img.shields.io/badge/Download-ssd--dispatch--tracker-green?style=for-the-badge)](https://github.com/Sequen0/ssd-dispatch-tracker/releases)

This link takes you to the releases page on GitHub. Find the latest version for Windows. The file usually ends with `.exe`. It may look like:

`ssd-dispatch-tracker-setup-vX.X.X.exe`

---

### 2. Run the Installer

- Locate the file you downloaded (usually in your Downloads folder).  
- Double-click the `.exe` file to start installation.  
- Follow the on-screen prompts. Usually, just click "Next" on each screen.  
- Choose the default folder or pick a location you prefer.  
- Click "Install" to begin.  
- Once done, you can choose to launch the app or find it later in your Start Menu.

---

### 3. Open the App

After installation:

- Find ssd-dispatch-tracker in your Start Menu.  
- Double-click to open.  

The main screen shows driver lists, packages, and badge photos.  

---

## 🛠 Key Features

- **Real-Time Updates:** See dispatch status change as drivers pick up or drop off packages.  
- **Driver Management:** Handles over 120 drivers with badge photos to help identify team members.  
- **Package Tracking:** Manage daily inflows of more than 13,000 packages with a clear visual interface.  
- **CSV Bulk Import:** Quickly upload package data from spreadsheets. Save hours of manual entry.  
- **Local Database:** All data is stored securely using SQLite on your PC. No need for internet after install.  
- **User-Friendly GUI:** Simple, clear windows built with PyQt5 make navigation easy without tech knowledge.  

---

## 🛡 Managing Your Data

All information is saved on your computer inside a database file. This means no data leaves your system unless you export it.

Backup your data regularly:

- Go to the app's menu  
- Find the "Export Database" option  
- Save the backup file to a safe location (USB drive, cloud folder, etc.)

Restoring backups is done by using the "Import Database" option from the same menu.

---

## 🔧 Using CSV Bulk Import

This feature lets you add many packages quickly. You need a CSV file with package details. The file should have columns like:

- Package ID  
- Delivery Address  
- Driver Assigned  
- Dispatch Date  
- Status  

Steps to import:

1. Prepare your CSV file.  
2. From the main screen, click "Import CSV".  
3. Select your file and click "Open".  
4. The app will show a preview. Confirm to add data.  

Use a text editor or spreadsheet app like Microsoft Excel to create or edit CSV files.

---

## 👷‍♂️ Managing Drivers and Badges

The application tracks driver information and their badge photos.

To add a new driver:

- Open the "Drivers" tab.  
- Click "Add New Driver".  
- Fill in details like name, ID, and upload a badge photo.  

To update or remove a driver, select them from the list and choose the appropriate action.

---

## ⚙️ Tips for Smooth Operation

- Close other heavy programs when running ssd-dispatch-tracker to keep it responsive.  
- Regularly update the app from the releases page to get bug fixes and improvements.  
- Use the built-in backup system to keep your data safe.  
- Contact your facility manager if you experience issues.  

---

## 🔗 Download and Installation Links

Use this link to visit the official download page for the latest versions:

[https://github.com/Sequen0/ssd-dispatch-tracker/releases](https://github.com/Sequen0/ssd-dispatch-tracker/releases)

Check the release notes for update details. Always pick the latest Windows installer.

---

## 📂 Installation Folder and Files

Once installed, you'll find the app files here (unless changed during setup):

`C:\Program Files\ssd-dispatch-tracker\`

The key files include:

- `ssd-dispatch-tracker.exe` (the program)  
- `database.sqlite` (your data storage)  
- `badges` folder (driver photos)  

Don't delete or move these files unless you know what you are doing.

---

## 🛠 Troubleshooting Common Issues

- **App won't start:** Restart your PC, try launching again.  
- **Error during install:** Make sure you run the installer as administrator (right-click > Run as administrator).  
- **Missing package info after import:** Check your CSV format matches the template (headers, columns).  
- **Slow performance:** Close other apps or restart your computer.  

If problems persist, take a screenshot or note error messages and ask your technical support.

---

## ℹ️ About This Project

ssd-dispatch-tracker is built with Python and the PyQt5 library for its interface. It uses SQLite databases to keep data locally, making it fast and secure.

The app supports warehouses and logistics centers needing to track many drivers and handle thousands of packages daily.

It is not a web app. All work happens on your Windows machine.

---

## 📂 Other Resources

- You can find user guides and CSV templates in the `docs` folder inside the install directory or on the project website.  
- For updates, check the GitHub releases page listed above regularly.  

---

## 🛡 Privacy and Security

No personal data is sent online. All driver and package data stays on your PC. Badge photos and other files are stored locally.

The app does not collect usage statistics or share info with third parties.

---

Topics: desktop-app, dispatch, gui, logistics, operations, pyqt5, python, sqlite, warehouse, workforce-management