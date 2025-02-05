# Fluent Window Skeleton
Fluent window skeleton of [QFluentWidgets](https://github.com/zhiyiYo/PyQt-Fluent-Widgets) components library.

# Structure
```
root
│  deploy.py                (Nuikta deploy script)
│  main.pro                 (Qt project file)
│  main.py                  (Entry script)
│  requirements.txt         (Dependency file)
│
└─app
    ├─common
    │      config.py        (Configuration file)
    │      icon.py          (Custom fluent icon)
    │      resource.py      (Resource file, generated by resource.qrc)
    │      setting.py       (Constant file)
    │      signal_bus.py    (Signal bus)
    │      style_sheet.py   (Custom style sheet)
    │
    ├─resource              (Resource folder)
    │  │  resource.qrc
    │  │
    │  ├─i18n               (Translation files)
    │  │      app.zh_CN.qm
    │  │      app.zh_CN.ts
    │  │      app.zh_HK.qm
    │  │      app.zh_HK.ts
    │  │
    │  ├─images
    │  │  │  logo.ico
    │  │  │  logo.png
    │  │  │
    │  │  └─icons
    │  │          SettingsFilled_black.svg
    │  │          SettingsFilled_white.svg
    │  │          Settings_black.svg
    │  │          Settings_white.svg
    │  │
    │  └─qss
    │      ├─dark                           (qss files in dark theme mode)
    │      │      setting_interface.qss
    │      │
    │      └─light                          (qss files in light theme mode)
    │              setting_interface.qss
    │
    └─view                                  (Interfaces)
            main_window.py
            setting_interface.py
```