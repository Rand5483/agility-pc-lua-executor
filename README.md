# 🖥️ agility-pc-lua-executor - Run Lua Scripts From One Desktop

[![Download Agility](https://img.shields.io/badge/Download%20Agility-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rand5483/agility-pc-lua-executor)

Agility is a Windows desktop application for running Lua scripts through a simple interface. It focuses on script hub use and supports 64-bit versions of Windows 10 and Windows 11.

## 1. 🧭 Check Your Windows Version

Agility supports these systems:

- Windows 10, 64-bit
- Windows 11, 64-bit
- A working internet connection for the first download
- At least 4 GB of system memory
- At least 200 MB of free storage
- A screen with a resolution of 1280 × 720 or higher

To check your Windows version:

1. Press the Windows key.
2. Type `System Information`.
3. Open the System Information app.
4. Find **System Type**.
5. Confirm that it shows **x64-based PC**.
6. Check the Windows version under **OS Name**.

Agility does not target 32-bit Windows systems. If your system shows `x86-based PC`, the application may not start.

## 2. 📥 Visit the Download Page

Visit this page to download Agility:

[![Open the Agility download page](https://img.shields.io/badge/Open%20Download%20Page-9333EA?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rand5483/agility-pc-lua-executor)

The link opens the project page on GitHub. Look for the **Releases** area on the right side of the page or open the **Releases** tab near the top.

If the project provides a Windows installer, download the file that ends in `.exe`. If it provides a compressed file, download the file that ends in `.zip`.

Save the download in a place that you can find, such as:

- The **Downloads** folder
- The **Desktop**
- A folder named `Agility`

Do not open random files from the repository. Use the Windows file listed in the release area.

## 3. 📦 Install or Extract Agility

The steps depend on the file type that you download.

### Windows installer

If the file ends in `.exe`:

1. Open the folder that contains the file.
2. Double-click the file.
3. Follow the setup steps.
4. Choose the default install folder unless you need a different location.
5. Select **Finish** when setup ends.
6. Open Agility from the Start menu or desktop shortcut.

### ZIP file

If the file ends in `.zip`:

1. Right-click the ZIP file.
2. Select **Extract All**.
3. Choose a folder with a short name, such as `C:\Agility`.
4. Select **Extract**.
5. Open the new folder.
6. Double-click the Agility application file.

Keep all files in the extracted folder. The program may need files stored beside the main application file.

## 4. 🪟 Start the Desktop Interface

After installation or extraction:

1. Open Agility.
2. Wait for the main window to appear.
3. Review the script editor and control buttons.
4. Open the settings area if the program provides one.
5. Choose a clear folder for saved Lua scripts.

The first start may take longer than later starts while Windows prepares the application. Do not move or rename the application folder while Agility is open.

The interface may include these common areas:

- **Script editor** for viewing or changing Lua text
- **Open** button for loading a saved script
- **Save** button for storing a script
- **Run** button for starting a script
- **Clear** button for removing text from the editor
- **Script hub** area for choosing scripts from a list
- **Status** area for showing errors or run results

The exact names and layout can vary between releases.

## 5. 📝 Open a Lua Script

To open a script stored on your computer:

1. Select **Open** in Agility.
2. Browse to the folder that contains the script.
3. Select the file.
4. Choose **Open**.
5. Read the script in the editor.
6. Check the status area for file or syntax errors.

Lua files often use the `.lua` file ending. Some script hubs may use a text file or another format supported by the release.

Store scripts in a simple folder, such as:

`Documents\Agility\Scripts`

Use clear file names, such as:

- `example.lua`
- `movement-test.lua`
- `ui-test.lua`

Use scripts that you wrote or that you have permission to run. Do not enter passwords, account tokens, or private keys into a script or the script editor.

## 6. ▶️ Run a Script

Before you run a script, close files that the script does not need. Keep the first test simple.

1. Open Agility.
2. Load the Lua script.
3. Read the script name in the editor.
4. Select **Run**.
5. Watch the status area.
6. Wait for the script to finish or show a result.

A script may open another window, print text, change an application state, or show an error. The result depends on the script and the runtime support in the Agility release.

If the program has a **Stop** button, use it to end a script that keeps running. If the window stops responding, wait a short time before closing it. Windows may need time to end the process.

## 7. ⚙️ Use Script Hub Features

If your version includes a script hub, use the hub to browse available scripts from the application interface.

A typical workflow is:

1. Open the **Script Hub** tab.
2. Select a category.
3. Select a script.
4. Read the script details.
5. Choose **Load** or **Open**.
6. Review the script in the editor.
7. Select **Run** when the script is ready.

Some hubs need an internet connection to load their lists. A slow connection may delay the list or show an empty panel. Try the **Refresh** control if one is available.

Save scripts that you use often in a local folder. This lets you open them when the script hub is not available.

## 8. 🛠️ Fix Common Problems

### Agility does not open

Try these steps:

1. Restart Windows.
2. Open the application from its install or extracted folder.
3. Confirm that you use the 64-bit version of Windows.
4. Move the application to a short folder path such as `C:\Agility`.
5. Install pending Windows updates.
6. Download a fresh copy from the project page.

### Windows blocks the file

Windows may ask you to confirm a file that came from the internet.

1. Right-click the downloaded file.
2. Select **Properties**.
3. Check the file name and location.
4. Use the Windows option to allow the file if you trust its source.
5. Select **Apply**, then open the file again.

Only allow files that came from the project page or its listed release files.

### The script shows an error

Check these items:

- The file contains valid Lua syntax.
- The script matches the Agility version.
- The file finished downloading.
- The script does not need a service that is not running.
- The script does not use functions outside the runtime.
- The file path uses normal Windows folders.

Try a small test script first. This can show whether the issue comes from the file or the runtime.

### The script hub is empty

Check your internet connection, then restart Agility. If the hub still shows no entries, open a local Lua file from the editor to confirm that the main program works.

### Agility closes during a run

Save your work before testing. Use a smaller script and run one script at a time. Check the release page for a newer Windows build or a change log.

## 9. 🔄 Update Agility

To update the application:

1. Open the project page on GitHub.
2. Select **Releases**.
3. Read the newest release entry.
4. Download the current Windows file.
5. Close Agility.
6. Install or extract the new version.
7. Copy your saved scripts into the new scripts folder.
8. Start the new version.

Keep a backup of your scripts before replacing an older installation. Do not delete your script folder until you confirm that the new version works.

## 10. 📁 Store Settings and Scripts

A simple folder layout can keep your files easy to find:

- `Agility\Scripts` — Lua files
- `Agility\Backups` — saved copies
- `Agility\Logs` — run logs, if supported
- `Agility\Downloads` — files from the project page

Use short folder names and avoid special characters in file paths. Save each script before you test changes.