**Shortcut Name:** Restart to BIOS
**Purpose:** Restarts the system and boots directly into BIOS/UEFI settings.

---

### 📌 What It Does:

This shortcut uses the Windows `shutdown` command with specific parameters:

```
shutdown /r /fw /t 1
```

* `/r` → Restarts the computer.
* `/fw` → Ensures the computer enters firmware (BIOS/UEFI) on next boot.
* `/t 1` → Sets a 1-second delay before the restart begins. 

---

### 🛠️ Setup Instructions:

1. **Create the Shortcut:**

   * Right-click on an empty area of your Desktop.
   * Choose **New > Shortcut**.
   * In the location box, type:

     ```
     shutdown /r /fw /t 1
     ```
   * Click **Next** and name the shortcut: `Restart to BIOS`.

2. **Enable Administrator Privileges:**

   * Right-click the new shortcut > **Properties**.
   * Click the **Advanced…** button.
   * Check the box for **Run as administrator**.
   * Click **OK** and then **Apply**.

---

### ⚠️ Important Notes:

* This shortcut **must be run as administrator** to work correctly.
* It will **immediately restart your PC** with **only 1 second delay**, so **save all work before using**.
* This works only on systems with **UEFI firmware** (most modern PCs).
