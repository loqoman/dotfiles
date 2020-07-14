## Directory Structure
---
#### `lain`
- One of the libraries used in the theme
#### `freedesktop`
- A library used in the theme
#### `themes` 
- Folder containing all the themes
#### kUbuntu Branch
- A seperate branch is mainted for kUbuntu-specific changes. At the moment, these only consist of a different terminal name (`konsole` vs. `gnome-terminal`), but as enviroments diverge both versions need to be easily accessable. In the future, master may be renamed to a more descriptave name.


## Issue Tracking
---
- TODO: Clear out all unused themes
	- Worth noting that this process will involve changing how `rc.lua` opens the theme folder, and ideally all the old code would be cut out
- TODO: Consoldate all library folders into one place
- TODO: Rebrand, chaning name
- TODO: Remove the 'mail' icon in the taskbar
- TODO: Debug the 'HDD' icon / dependancy
- TODO: Debug the 'music' feature
- TODO: Support multiple monitor backgrounds with auto-detection
