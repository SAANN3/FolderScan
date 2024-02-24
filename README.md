# Folder scanner
Program written in electron , that shows size of your folders on drive.
### Screenshot
!![Untitled](https://github.com/SAANN3/FolderScan/assets/95036865/122f3a21-96a1-4b29-b827-6a7c2da3c52f)
 | 
## Installation
[Download](https://github.com/SAANN3/FolderScan/releases) a linux binary or windows installer
## Usage
Run,select disk and let it scan (3~10 minutes), then navigate using mouse and buttons

Also while scanning program will be showing itself as not responing, due to heavy task and ui is still going to update.

### Or if you prefer to compile from source
#### For linux
```
https://github.com/SAANN3/FolderScan
cd FolderScan
npm install
npm run build
npm run build-linux
npm run electron-pack
```
Appimage will be placed in dist folder
#### For windows
```
https://github.com/SAANN3/FolderScan
cd FolderScan
npm install
npm run build
npm run build-windows
npm run electron-pack
```
Installer will be placed in dist folder

