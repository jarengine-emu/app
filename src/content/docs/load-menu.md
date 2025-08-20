---
title: "Load Menu"
description: "Complete guide to loading and managing MIDlet applications in JarEngine"
order: 4
category: "Menus"
---

# Load Menu Documentation

The **Load** menu is your gateway to running MIDlet applications in JarEngine. This menu provides all the tools you need to load, manage, and organize your MIDlet collection.

## 📁 Menu Items

### Load JAR
**Purpose**: Open and run MIDlet JAR files from your local file system.

**How to Use**:
1. Click **Load JAR** from the Load menu
2. Navigate to your MIDlet JAR file
3. Select the file and click Open
4. The MIDlet will load and start automatically

**Supported Formats**: Standard JAR files containing MIDlet applications

**Tips**:
- Make sure your JAR file contains valid MIDlet classes
- Large JAR files may take a moment to load
- Check the console for any loading errors

### Fetch via URL
**Purpose**: Download and run MIDlets directly from web URLs.

**How to Use**:
1. Click **Fetch via URL** from the Load menu
2. Enter the complete URL to your MIDlet JAR file
3. Click OK to start the download
4. The MIDlet will automatically load once downloaded

**Supported URLs**: HTTP and HTTPS URLs pointing to JAR files

**Tips**:
- Ensure the URL points directly to a JAR file
- Check your internet connection before downloading
- Some servers may require authentication

### Terminate
**Purpose**: Stop the currently running MIDlet application.

**Keyboard Shortcut**: `Ctrl+W`

**How to Use**:
1. Click **Terminate** from the Load menu
2. Or use the keyboard shortcut `Ctrl+W`
3. The current MIDlet will stop and return to the main interface

**When to Use**:
- When a MIDlet becomes unresponsive
- To stop a running application before loading another
- To free up system resources

### Recents Library
**Purpose**: Quick access to recently opened MIDlet applications.

**Features**:
- **Smart Organization**: Automatically tracks your recently used MIDlets
- **Visual Icons**: Shows MIDlet icons when available
- **Suite Names**: Displays friendly names instead of file paths
- **Deduplication**: Automatically removes duplicates

**How to Use**:
1. Hover over **Recents Library** in the Load menu
2. Select any previously opened MIDlet from the list
3. The MIDlet will load immediately

**Benefits**:
- Faster access to frequently used applications
- No need to navigate through file dialogs
- Maintains your MIDlet usage history

### Exit
**Purpose**: Close the JarEngine application completely.

**Keyboard Shortcut**: `Ctrl+Q`

**How to Use**:
1. Click **Exit** from the Load menu
2. Or use the keyboard shortcut `Ctrl+Q`
3. Confirm if you have unsaved work

**Note**: This will close all running MIDlets and the application. Make sure to save any important work before exiting.

## 🔧 Advanced Features

### Automatic MIDlet Detection
JarEngine automatically detects and validates MIDlet files, ensuring only compatible applications are loaded.

### Error Handling
The Load menu provides clear error messages for:
- Invalid JAR files
- Missing MIDlet classes
- Network download failures
- File permission issues

### Memory Management
- Automatically manages memory when loading multiple MIDlets
- Provides feedback on system resource usage
- Optimizes loading for large applications

## 🚀 Best Practices

1. **Organize Your MIDlets**: Keep your JAR files in a dedicated folder for easy access
2. **Use Recents**: Take advantage of the Recents Library for frequently used applications
3. **Check Compatibility**: Ensure your JAR files are compatible with the MIDP version you're targeting
4. **Monitor Resources**: Use the Terminate option to free up resources when needed

## ❓ Troubleshooting

**Problem**: JAR file won't load
- **Solution**: Check if the file is corrupted or incomplete
- **Solution**: Verify the JAR contains valid MIDlet classes

**Problem**: URL download fails
- **Solution**: Check your internet connection
- **Solution**: Verify the URL is accessible and points to a JAR file

**Problem**: MIDlet crashes on load
- **Solution**: Use the Terminate option and try loading again
- **Solution**: Check the console for error messages

---

*The Load menu is designed to make MIDlet management simple and efficient. Whether you're working with local files or downloading from the web, this menu provides all the tools you need to get your MIDlets running quickly.*
