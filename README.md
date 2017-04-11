[Original nvm-windows repository](https://github.com/coreybutler/nvm-windows)

This version of nvm-windows is suited for creating scripts to auto-update Node.js. In this version, whenever "nvm install [version]" is called, "nvm use [version]" is automatically called without needing further action or commands.

To create a Node.js auto-updating script, you simply need to create a script that runs "nvm install latest", and it will install the latest version and switch to it. Make sure nvm-windows is actually enabled by running "nvm on" after setting up nvm-windows.
