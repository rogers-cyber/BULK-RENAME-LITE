# BULK RENAME LITE – Simple Offline Batch File Renamer v1.0.0

BULK RENAME LITE v1.0.0 is a lightweight desktop application designed for fast and safe batch file renaming. It allows users to rename thousands of files in seconds using customizable patterns, preview-based validation, and conflict-safe processing.

Built with a modern Tkinter + ttkbootstrap interface, BULK RENAME LITE focuses on simplicity, speed, and offline usability. It supports drag-and-drop file loading, recursive folder scanning, and real-time rename preview before applying changes.

------------------------------------------------------------
WINDOWS DOWNLOAD (EXE)
------------------------------------------------------------

Download the latest Windows executable from:

https://matetools.gumroad.com

- No Python installation required  
- Standalone Windows executable  
- Fully offline batch renaming tool  
- Lightweight and fast performance  
- Simple drag & drop workflow  

------------------------------------------------------------
FEATURES
------------------------------------------------------------

CORE CAPABILITIES

- ✏️ Batch rename thousands of files quickly
- 📂 Drag & Drop file and folder support
- 📁 Recursive folder scanning (deep file collection)
- 👁 Live rename preview before applying changes
- 🔢 Custom naming patterns with variables
- ⚡ High-speed multithreaded rename execution
- 🧠 Smart conflict detection and auto-resolution
- 🧹 Session reset and file clearing system
- 🚫 Safe cancel operation during processing
- 💻 Fully offline operation (no internet required)

NAMING PATTERN SYSTEM

Supports flexible renaming templates:

- {name} → Original filename (without extension)
- {ext} → File extension
- {num} → Auto-incrementing number (zero-padded)
- {date} → Current date (YYYYMMDD format)

Example:
file_{num}{ext}
image_{date}_{num}{ext}

OUTPUT SAFETY

- Prevents filename overwrites automatically
- Adds suffix (1), (2), etc. on conflicts
- Ensures no data loss during rename operations
- Skips missing or invalid files safely
- Maintains folder structure integrity

FILE HANDLING

- Supports all file types
- Multi-folder batch processing
- Duplicate file filtering
- Stable handling of large file lists
- Preserves original directory structure
- Fast OS-level renaming using os.rename

USER INTERFACE

- Modern ttkbootstrap UI (Dark theme)
- Clean file tree preview system
- Editable rename pattern input
- Start index control for numbering
- Real-time progress bar
- Live status updates
- Menu-based workflow (File / Help)
- About window with app info and links

------------------------------------------------------------
USAGE GUIDE
------------------------------------------------------------

1. Add Files or Folder  
Use "Add Files" or "Add Folder" to load items.

2. Set Rename Pattern  
Define your naming format using variables like {num}, {name}, {ext}.

3. Preview Changes  
Click "Preview" to review new filenames before applying.

4. Start Renaming  
Click "Rename" to apply changes to all selected files.

5. Monitor Progress  
Watch real-time progress bar during renaming.

------------------------------------------------------------
PATTERN EXAMPLES
------------------------------------------------------------

- file_{num}{ext}
- image_{date}_{num}{ext}
- document_{name}_{num}{ext}
- backup_{date}{ext}

------------------------------------------------------------
SAFETY DESIGN
------------------------------------------------------------

BULK RENAME LITE ensures safe file operations through:

- Pre-renaming preview system
- Automatic conflict resolution
- Existence checks before renaming
- Exception handling during OS operations
- Threaded execution to prevent UI freezing
- Cancel-safe processing loop

------------------------------------------------------------
ERROR HANDLING & RELIABILITY
------------------------------------------------------------

- Skips missing or moved files automatically
- Handles permission and OS errors gracefully
- Continues processing even if individual files fail
- Logs errors to console for debugging
- Prevents duplicate filename collisions
- Maintains stable UI during heavy operations

------------------------------------------------------------
INTENDED USE
------------------------------------------------------------

BULK RENAME LITE is ideal for:

- Organizing large photo collections
- Renaming downloaded files in bulk
- Structuring project assets
- Cleaning messy file directories
- Preparing datasets for machine learning
- Managing media libraries efficiently
- Automating repetitive renaming tasks

------------------------------------------------------------
UPGRADE TO PRO
------------------------------------------------------------

Upgrade to BULK RENAME PRO for advanced features:

- Regex-based renaming engine
- Metadata-based renaming (EXIF, EXIF date, etc.)
- Advanced filtering (by extension, size, date)
- Undo / rollback system
- Cloud folder integration
- Saved renaming presets
- Multi-rule batch pipelines
- GUI workflow automation builder

Website:

https://matetools.gumroad.com

------------------------------------------------------------
ABOUT
------------------------------------------------------------

BULK RENAME LITE is developed by Mate Technologies, focused on building lightweight, offline desktop tools for productivity, automation, and file management workflows.

Website:

https://matetools.gumroad.com

© 2026 Mate Technologies  
All rights reserved.

------------------------------------------------------------
LICENSE
------------------------------------------------------------

BULK RENAME LITE is distributed as commercial software.

License terms:

- Personal and commercial usage allowed  
- Redistribution or resale as a competing product is prohibited  
- Repackaging or rebranding for resale is prohibited  
- Source modification allowed for internal/private use  
- Compiled executable usage permitted under license  

For commercial licensing or enterprise deployment, contact the developer.

------------------------------------------------------------
📷 PREVIEW
------------------------------------------------------------

<img alt="BULK RENAME LITE Main Interface" src="https://github.com/rogers-cyber/BULK-RENAME-LITE/blob/main/BulkRenameLITE%20-%20Main%20Interface.png" />

<img alt="BULK RENAME LITE Rename Preview" src="https://github.com/rogers-cyber/BULK-RENAME-LITE/blob/main/BulkRenameLITE%20-%20Preview.png" />

<img alt="BULK RENAME LITE Rename Result" src="https://github.com/rogers-cyber/BULK-RENAME-LITE/blob/main/BulkRenameLITE%20-%20Rename.png" />