---
layout: app

permalink: /OpenTodoList/
description: A note and task managing application

icons:
  - OpenTodoList/icons/128x128/net.rpdev.OpenTodoList.png

screenshots:
  - OpenTodoList/screenshot.png

authors:
  - name: mhoeher
    url: https://github.com/mhoeher

links:
  - type: GitHub
    url: mhoeher/opentodolist
  - type: Download
    url: https://github.com/mhoeher/opentodolist/releases

desktop:
  Desktop Entry:
    Type: Application
    Name: OpenTodoList
    Exec: OpenTodoList %F
    Icon: net.rpdev.OpenTodoList
    Comment: A note and task managing application
    Terminal: false
    Categories: Utility
  AppImageHub:
    X-AppImage-UpdateInformation: zsync|https://gitlab.com/rpdev/opentodolist/-/jobs/artifacts/3.11.0/raw/OpenTodoList-x86_64.AppImage.zsync?job=ubuntu_appimage
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---
