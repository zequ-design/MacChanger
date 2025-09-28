# MacChanger-GUI

**Simple and visual MAC address changer for Windows 10/11**

---

## Description

MacChanger-GUI is a lightweight PowerShell-based application that allows you to **quickly generate a new MAC address**, apply it to your active network adapter, and restore the original MAC address if needed. The tool uses a clean graphical interface with buttons for easy operation and displays the old, current, and new MAC addresses.

- No command-line knowledge required  
- Works on Windows 10 and Windows 11  
- Generates fully valid MAC addresses  
- Allows restoring your original MAC address  
- Copies newly generated MAC to clipboard automatically  

---

## Features

1. **Generate New MAC** – Randomly creates a locally administered MAC address and applies it.  
2. **Restore MAC** – Restores your original MAC address.  
3. **Display MAC Addresses** – Shows old, current, and new MAC in the interface.  
4. **Quit Button** – Closes the application safely.  

---

## Usage

1. Make sure to run the **EXE as Administrator**, otherwise changing the MAC will fail.  
2. Launch `MacChanger-GUI.exe`.  
3. Use the buttons:  
   - **Generate New MAC** – Creates a new random MAC and applies it.  
   - **Restore MAC** – Restores the original MAC.  
   - **Quit** – Closes the app.  
4. Check the **Current MAC** label to verify the applied address.  

---

## Requirements

- Windows 10 / 11  
- PowerShell (included in Windows)  
- Administrative privileges  

---

## Notes

- Changing the MAC address might temporarily disconnect your network adapter.  
- The new MAC is copied to the clipboard automatically for convenience.  
- Always restore your original MAC if needed using the **Restore MAC** button.  

---

## License

MIT License
