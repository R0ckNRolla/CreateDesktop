# CreateDesktop

Creates a hidden Windows 10 virtual desktop.

## Details

Visual Studio 2017 32/64-bit native console application written in C++. When run creates a hidden virtual Windows 10 desktop and toggles to it. To toggle back, press Ctrl+Alt+E. The virtual desktop remains active but invisible even after the command has terminated. Run the command again to get back to it.

### Using

Run CreateDesktop.exe from File Explorer or a shell.

Press Ctrl+Alt+E to toggle back to the source desktop.

Any key then exists (the prompt will be taken away in a future version).

Run CreateDesktop.exe to return to the hidden virtual desktop to find it as you left it.

### Known Issues

Start Menu and other Windows-specific icons on the taskbar don't respond on the virtual desktop.

## Built With

* [Visual Studio Community 2017](https://www.visualstudio.com/) - The IDE used

## Authors

* **MalwareTech** - *Initial work* - [MalwareTech](https://github.com/MalwareTech)
* **Andreas Toth** - *UNICODE and clean-ups* - [MrAndreasToth](https://github.com/mrandreastoth)