# Cursor IDE Icon

This repository provides a custom icon for the Cursor IDE that more closely resembles the Visual Studio Code icon. The similar appearance helps maintain muscle memory and workflow efficiency when transitioning to using Cursor (from VS Code).

<img src="Cursor.png" alt="Cursor Icon" width="200px">

## How to install

Down the `.icns` [file from this repo](icon.icns), and then in Finder:

1) Right-click on the Cursor application
2) Select "Get Info" (or use ⌘ + I)
3) Drag your new icon file onto the current icon in the top-left corner of the Info window
4) If prompted, enter your administrator password


If that doesn't work, you can try this alternative method:

```bash
# Navigate to the Cursor.app location (usually in Applications)
cd /Applications/Cursor.app/Contents/Resources/

# Backup the original icon
sudo cp icon.icns icon-backup.icns

# Replace with your new icon (needs to be named icon.icns)
sudo cp /path/to/your/new/icon.icns icon.icns
```
