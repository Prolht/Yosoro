<p align="center">
  <img src="./app/views/assets/images/logo.png" width="200"/>
  <h3 align="center">Yosoro</h3>
  <p align="center">Beautiful Cloud Drive Markdown NoteBook Desktop App</p>
  <p align="center">
    <img src="https://img.shields.io/badge/platform-masOS%20%7C%20Linux%20%7C%20Windows-lightgrey.svg?style=flat-square" />
  </p>
  <p align="center">
    <img src="https://img.shields.io/github/release/iceend/yosoro.svg?style=flat-square" />
    <img src="https://img.shields.io/travis/IceEnd/Yosoro.svg?style=flat-square">
    <img src="https://img.shields.io/github/license/IceEnd/Yosoro.svg?style=flat-square" />
  </p>
  <p align="center">
    <img src="https://img.shields.io/github/downloads/IceEnd/Yosoro/total.svg?style=flat-square">
  </p>
</p>

## Download

The latest version of Yosoro for macOS, linux and Windows is available [here](https://github.com/IceEnd/Yosoro/releases).

**macOS 10.9+, Windows 7+ & Linux are supported.**

## Features

- Create notebook & Write note
- Support Markdown syntax
- Delete & Restore
- Synchronize with Cloud Drive(OneDrive is supported)
- Image upload (GitHub is supported).
- Export notes as markdown or html or pdf
- Update Notification

You can read [Wiki](https://github.com/IceEnd/Yosoro/wiki) & [CHANGELOG](./CHANGELOG.md) to get more information.

## Demo

### Write Notes

![write](https://t1.picb.cc/uploads/2018/05/13/2vBxK7.gif)

### Upload Image

![image](https://raw.githubusercontent.com/IceEnd/Yosoro-Img/img/yosoro/2018-07-27.00.47.27-image.gif)

### File Syncing

![sync](https://t1.picb.cc/uploads/2018/05/13/2vBRbs.gif)

## Screenshots

### macOS

![screenshot-osx.png](https://raw.githubusercontent.com/IceEnd/Yosoro-Img/img/yosoro/2018-07-27.00.49.24-image.png)

### Windows

![screenshot-window.png](https://raw.githubusercontent.com/IceEnd/Yosoro-Img/img/yosoro/2018-07-26.17.43.22-image.png)

### linux

![screenshot-linux](https://raw.githubusercontent.com/IceEnd/Yosoro-Img/img/yosoro/2018-07-27.00.22.40-linux.png)

## Quick Start

### Install

```shell
yarn
```

### Dev Tools Extension

```shell
cp ./config/devconfig.example.json ./config/devconfig.json
```

### Run Main Process

```shell
npm run dev:main
```

### Run Renderer Process

```shell
npm run dev:renderer
```

### Build

```shell
npm run build:all|main|renderer
```

### Package

```
npm run packager:mac|win|win:64|linux
```

## License

GPL-3.0 © [Alchemy](./LICENSE)
