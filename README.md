## Build from source on linux:

```
git clone https://github.com/maciejmotyka/Brain.fm-Desktop-Client.git
cd Brain.fm-Desktop-Client
npm install
## to test if it works
npm start
## package for linux
npm run package:linux
```

The app is now in the ./out directory. Copy it to some sensible location e.g.
`/opt` and put a link the binary in the path e.g. `/usr/local/bin` 
```
sudo cp -r ./out/brainfm-linux-x64/ /opt
sudo ln -s /opt/brainfm-linux-x64/brainfm /usr/local/bin/brainfm
```

**Original readme**
---

# Brain.fm-Desktop-Client
https://brain.fm Desktop client

Simple Electron app as a desktop client for Brain.fm

Runs in a standalone window with keyboard media button control for play/pause.

## Download

You can download the latest binaries for macOS, Windows, and Linux [here](https://github.com/Dinius/Brain.fm-Desktop-Client/releases/latest).

## Screenshots
![macos screenshot](screenshots/osx.png)

![windows screenshot](screenshots/windows2.png)
