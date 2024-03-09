# kap-cam

> A [Kap](https://github.com/wulkano/kap) plugin that adds a Loom-like Webcam overlay to recordings.

## Installation

_(this does not currently work as the package is yet to be crawled by `npms.io`)_

```
cd ~/Library/Application\ Support/Kap/plugins/

npm remove kap-camera

git clone https://github.com/clearlysid/kap-cam

npm link ./kap-cam

sed -i '' 's/"dependencies": {/"dependencies": {\n    "kap-cam": "latest",/' package.json

npm link
```

1. Open Kap `Preferences`
2. Select the `Plugins` pane, and switch to `Discover` tab.
3. In the list of plugins, find `cam` and toggle it on.

## Usage

To enable or disable the overlay:

1. Right click the Kap menu icon or click the `…` icon in the cropper.
2. In the `Plugins` menu, check or uncheck `Show Camera`

Note that the Camera window does not appear until you start a recording.

## Notes

This is based off of [@karaggeorge's](https://github.com/karaggeorge) [kap-camera](https://github.com/karaggeorge/kap-camera/) plugin. The repo for it seemed to be inactive and I really wanted a more Loom-like flavour to its UI, so I decided to fork and maintain my own. Feel free to raise issues, leave feedback or contribute in any way you see fit. Cheers! 🥂

## Demo

![demo](https://user-images.githubusercontent.com/30227512/193472451-810ad0e7-a90f-4b06-b819-28347f1cb771.gif)
