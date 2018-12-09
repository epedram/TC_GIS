# TC_GIS
Total Commander Bundle for Data Scientists and GIS Users

## Modular Directory Structure
```
..\Disk Root\
├── Commander
│   ├── Settings
│   │   ├── wcx_plugins.ini
│   │   ├── wdx_plugins.ini
│   │   ├── wfx_plugins.ini
│   │   ├── wlx_plugins.ini
│   │   ├── colors.ini
│   │   ├── shortcuts.ini
│   │   ├── diemenu.ini
│   │   ├── searches.ini
│   │   ├── associations.ini
│   │   ├── pakers.ini
│   │   ├── tabs.ini
│   │   ├── history.ini (including: command line, search, select, rename, new files and folders)
│   │   └── *.ini
│   ├── Plugins
│   │   ├── WCX
│   │   ├── WDX
│   │   ├── WFX
│   │   ├── WLX
│   │   ├── Packers
│   │   ├── *.bar
│   │   └── *.br2
│   ├── External_Tools
│   │   ├── Editors
│   │   │   ├── ...
│   │   ├── Viewers
│   │   │   ├── ...
│   │   ├── TC_Tools
│   │   ├── File_Managers
│   │   ├── System_Tools
│   │   ├── Network_Tools
│   │   ├── Disk_Tools
│   │   └── Misc_Tools
│   │       └── ...
│   ├── Language
│   ├── Graphics
│   ├── Help
│   └── Misc (ocx/dll registration bat file)
├── Program binaries (including unmovable plugins binaries and settings)
└── wincmd.ini
```