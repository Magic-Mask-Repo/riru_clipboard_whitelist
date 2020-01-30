# Riru - Clipboard Whitelist

A module of [Riru](https://github.com/RikkaApps/Riru). Allow specific application access clipboard in background on Android 10.

## Requirements

* [Riru](https://github.com/RikkaApps/Riru) > 19 installed.
* Android 10



## Configure


* Add package to whitelist  
  Edit file `/data/misc/clipboard/whitelist.list` and add package name direct which you want.  
  One package name per line
  
* Check module injected  
  ```bash
  getprop sys.clipboard.whitelist
  ```

## Source

https://github.com/Kr328/Riru-ClipboardWhitelist

## Feedback

Telegram Group [Kr328 Riru Modules](https://t.me/kr328_riru_modules)
