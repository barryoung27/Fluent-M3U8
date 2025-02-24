<p align="center">
  <img width="15%" align="center" src="app/resource/images/logo.png" alt="logo">
</p>
  <h1 align="center">
  Fluent M3U8
</h1>
<p align="center">
  A cross-platform m3u8 downloader based on PySide6 and QFluentWidgets
</p>

<p align="center">

  <a style="text-decoration:none">
    <img src="https://img.shields.io/badge/Python-3.11.11-blue.svg?color=00B16A" alt="Python 3.11.11"/>
  </a>

  <a style="text-decoration:none">
    <img src="https://img.shields.io/badge/PySide-6.6.2-blue?color=00B16A" alt="PySide 6.6.2"/>
  </a>

  <a style="text-decoration:none">
    <img src="https://img.shields.io/badge/Platform-Win32%20|%20Linux%20|%20macOS-blue?color=00B16A" alt="Platform Win32 | Linux | macOS"/>
  </a>
</p>

<p align="center">
English | <a href="docs/README_zh.md">简体中文</a> | <a href="https://fluent-m3u8.org">官网</a>
</p>

![界面](docs/screenshot/主界面.png)

## Features
* Fully compatible with M3U8 and MPD video downloads
* Multi-threaded M3U8 download support
* Task management for downloads
* Sleek and user-friendly GUI


## Quick start
1. Create virtual environment:

    ```shell
    conda create -n fluent-m3u8 python=3.11
    conda activate fluent-m3u8
    pip install -r requirements.txt
    ```

2. Download [FFmpeg](https://www.ffmpeg.org/download.html) and [N_m3u8DL-RE](https://github.com/nilaoda/N_m3u8DL-RE/releases)

3. Place the executable files of ffmpeg and N_m3u8DL-RE in the `tools` directory.

3. Open Fluent M3U8:

    ```shell
    conda activate fluent-m3u8
    python Fluent-M3U8.py
    ```

## Deploy

1. Run deploy script:
    ```shell
    conda activate fluent-m3u8
    python deploy.py
    ```

2. Copy `tools` folder to the packaging folder:
   * For Windows and Linux: `dist/Fluent-M3U8.dist/tools`
   * For macOS: `dist/Fluent-M3U8.app/Contents/MacOS/tools`


## See also

- [zhiyiYo/QFluentWidgets](https://qfluentwidgets.com/)：A fluent design widgets library based on C++ Qt/PyQt/PySide. Make Qt Great Again.
- [nilaoda/N_m3u8DL-RE](https://github.com/nilaoda/N_m3u8DL-RE)：Cross-Platform, modern and powerful stream downloader for MPD/M3U8/ISM.
- [AresConnor/pyqt5_concurrent](https://github.com/AresConnor/pyqt5-concurrent)：A QThreadPool based task concurrency library.

## License
Fluent-M3U8 is licensed under GPLv3.

Copyright © 2025 by zhiyiYo.

