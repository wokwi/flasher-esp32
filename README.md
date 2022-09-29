# Javascript implementation of esptool

This repository contains a Javascript implementation of [esptool](https://github.com/espressif/esptool), a serial flasher utility for Espressif chips. Unlike the Python-based esptool, `esptool-js` doesn't implement generation of binary images out of ELF files, and doesn't include companion tools similar to [espefuse.py](https://github.com/espressif/esptool/wiki/espefuse) and [espsecure.py](https://github.com/espressif/esptool/wiki/espsecure).

`esptool-js` is based on [Web Serial API](https://wicg.github.io/serial/) and works in Google Chrome and Microsoft Edge, [version 89 or later](https://developer.mozilla.org/en-US/docs/Web/API/Serial#browser_compatibility).

## Live demo

Visit https://espressif.github.io/esptool-js/ to see this tool in action.

## Testing it locally

```
npm install
npm start
```

Then open http://localhost:5173 in Chrome or Edge.

## Creating a production bundle

```
npm run build
```

Then serve the contents of `dist/` directory.

## License

The code in this repository is Copyright (c) 2021 Espressif Systems (Shanghai) Co. Ltd, (c) 2022 CodeMagic Ltd. It is licensed under Apache 2.0 license, as described in [LICENSE](LICENSE) file.
