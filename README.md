# updater-vscode

### What is this?
Think of this as a "set-and-forget" housekeeper for Visual Studio Code on your Mac. It’s a simple script that makes sure your app is always the latest version and that your favorite settings are locked in across every user account on the computer.

### How it helps you:
* **Stays Current:** Every Monday morning at 9:00 AM, it checks if there’s a new version of VS Code. If there is, it handles the update for you.
* **Security First:** It checks a digital "fingerprint" on every download to make sure the file hasn't been tampered with or corrupted.
* **Consistent Settings:** It forces 132 specific settings (like turning off tracking, setting font sizes, and enabling auto-save) so you don't have to set them up manually every time.
* **Plays Nice:** It’s smart enough to leave your personal themes and unique extensions alone. It only touches the settings you've told it to manage.
* **Cleans Up:** It keeps a "vault" of the last 3 versions just in case you need to roll back, and it automatically deletes older files to save your disk space.

### How to use it:
1.  Save the script file as `updater-vscode`.
2.  Open your Terminal and make it runnable by typing:  
    `chmod +x updater-vscode`
3.  Run it once to set everything up:  
    `sudo ./updater-vscode`
    
*After that first run, the script moves itself to a permanent home and handles the Monday morning chores entirely on its own.*

### Reading the Summary Table:
When the script finishes, it shows you a quick report:
* **ENFORCED:** The number of "must-have" settings the script corrected.
* **PRESERVED:** Your own unique settings (like your favorite color theme) that the script ignored.
* **TOTAL:** The final count of all settings now active in your file.

---
**Created by:** Raajiv Rekha  
**Version:** 1.0
