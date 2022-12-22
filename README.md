# 3DS Theme Downloader (3DS TD)
An easy-to-use theme downloader for the 3DS.

# Setup
To start using 3DS TD, follow the steps that corrospond with your OS (operating system).
### WARNING!
When downloading the .ZIP file (from this GitHub repository) and extracting it, make sure to make a folder called (exactly) `themes` (all lower case) in the folder it extracted to!
### Windows
* Download the .msi (Windows Installer) from [here](https://nodejs.org/en/download/), and run it.
* Follow the steps to install Node.JS, this should also install `npm`.
* Click the Code button, and then Download ZIP in the dropdown on this GitHub repository's main page.
* Extract the ZIP that it downloads.
* Open the folder that was extracted (a.k.a root folder) and put your theme's .ZIP file in the `theme` folder.
* Run `installW.bat` that is in the root folder.
* Run `runW.bat` that is in the root folder.
  - Next time you want to start the app again, just run `runW.bat`.
* Open the link that is output in the Command Prompt window.
* Scan the QR code on your 3DS via the Anemone app.
### macOS
* Download the .pkg (macOS Installer) from [here](https://nodejs.org/en/download/), and run it.
  - Optional: If you have [`brew`](brew.sh) installed, open Terminal and run `brew install node.js npm`
* Follow the steps to install Node.JS, this should also install `npm`.
* Click the Code button, and then Download ZIP in the dropdown on this GitHub repository's main page.
* Extract the ZIP that it downloads.
* Open the folder that was extracted (a.k.a root folder) and put your theme's .ZIP file in the `theme` folder.
* Open `Terminal.app`, and type `cd` (then a space) and drag the root - If you extracted the root folder to your Desktop, it should look like this: `cd /Users/.../Desktop/3DS-TD/` (the folder might be named differently)
* Press Enter, then type `chmod +x installM.sh` and press Enter.
* Then type `chmod +x runM.sh` and press Enter.
* Close Terminal.app
* Run `installM.sh` that is in the root folder.
* Run `runM.sh` that is in the root folder.
  - Next time you want to start the app again, just run `runM.sh`.
* Open the link that is output in the Terminal window. You might need to hold Command and then click on the link to open it.
* Scan the QR code on your 3DS via the Anemone app.
### Ubuntu/Any Linux Distro
* Open Terminal
* Run `sudo apt-get install node.js`
* Click the Code button, and then Download ZIP in the dropdown on this GitHub repository's main page.
* Extract the ZIP that it downloads.
* Go back to Terminal
* `cd` into the extracted folder (a.k.a root folder)
* Run `npm i && npm start`.
  - Next time you want to start the app again, just `cd` into the root folder again and run `npm start`.
* Open the link that is output in the Terminal window. You might need to hold Command and then click on the link to open it.
* Scan the QR code on your 3DS via the Anemone app.
