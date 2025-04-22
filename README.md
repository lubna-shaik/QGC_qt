# QGC_qt
# QGroundControl AppImage (Linux)
This repository contains a ready-to-run **QGroundControl** AppImage, built using Qt 5.15.2 and packaged via WSL (Ubuntu). The AppImage includes all required dependencies to run the application on Linux systems.

## 🚀 How to Use (Linux / WSL)
### 1. 📥 Download the AppImage  
Go to this repository and download: `QGroundControl-Linux.AppImage`

### 2. 🔧 Make it Executable  
In your WSL (Ubuntu) terminal, go to the folder where the file was downloaded. Example:

cd /mnt/c/Users/lubna/Downloads
chmod +x QGroundControl-Linux.AppImage
Replace the path with your actual download location if different.

3. ▶️ Run the AppImage

./QGroundControl-Linux.AppImage
✅ The full GUI should launch successfully.

🛠 Notes
Built using Qt 5.15.2 on Ubuntu (WSL)

AppImage is standalone — no separate Qt installation needed

Works on most modern Linux environments

❗ Troubleshooting
If you see this error:

module "QtQuick.Controls" is not installed
➡️ Make sure you downloaded the latest AppImage from this repository.
