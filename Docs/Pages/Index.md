# LaunchPass
LaunchPass is a modified fork of [RetroPass](https://github.com/retropassdev/RetroPass) without this project would not exist & is a themeable frontend for Xbox/Xbox Series Retro Gaming Emulators!
![Logo](https://github.com/Misunderstood-Wookiee/LaunchPass/blob/d14ac0b559bae1aae99185a8be933d4af86664f2/Docs/LaunchPass.webp)
![Video](/Docs/collection.gif)

## Compatibility
- [Xenia Canary: Xbox Port](https://github.com/SirMangler/xenia)
- [Dolphin: Xbox Port](https://github.com/SirMangler/dolphin)
- [XBSX2: Xbox Port](https://github.com/TheRhysWyrill/XBSX2)
- [RetroArch: Xbox Port](https://www.retroarch.com/?page=platforms)
- [RetriX](https://github.com/Aftnet/RetriX)


## Usage
[Check out our Wiki for setup and usage intructions](https://github.com/Misunderstood-Wookiee/LaunchPass/wiki)

## Features

#### Limitations

 - Xbox Only
 - Optimized for Gamepad Only
 - Zipped content supported only if RetroArch, RetriX or other supported cores/emulators support reading the file extentsion.
 - No Automatic Image Scrapper, you must use Launchbox
 - EmulationStation support is discontinued sorry!
  

## Build Project?

1. Install Visual Studio 2019
2. Get the latest source code from Main/Dev branch or [release](../../releases/)
3. Open **RetroPass.sln**
4. Under **Package.appxmanifest** -> **Packing**, create and choose a different Certificate if needed.
5. Set **Configuration** to **Release**
6. Set **Platform** to **x64**
7. **Project** -> **Publish** -> **Create App Packages...**
8. Choose **Sideloading**, turn off **Enable automatic updates**
9. **Yes, select a certificate** or **Yes, use the current certificate**
10. Under **Architecture** check only **x64**
11. Package is built and ready to install.
12. Optionally, for smaller package size, it is safe to delete:
	- Add-AppDevPackage.resources
	- Dependencies\arm
	- Dependencies\arm64
	- Dependencies\x86
	- TelemetryDependencies
	- Add-AppDevPackage.ps1
	- Install.ps1

Feel free to fork the repository and further develop the app to your liking, but you must keep branding & give credit where due.

