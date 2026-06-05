# Pebble HF Web Firmware Updater

A web-based firmware updater for the **[Pebble HF](https://pebblehf.com)**. It runs entirely in your browser — no software to install — and flashes a firmware file to your radio over a USB-serial adapter.

## Compatibility

This tool currently only works with **STK500v1-compatible serial adapters**. An official adapter from the people behind the Pebble HF project may be coming soon.

It runs in **Chromium-based browsers only** — Chrome, Edge, Brave, or Opera — because it uses the browser's Web Serial feature.

## How to use it (the simple version)

1. **Plug your adapter into your computer** using its USB cable.
2. **Plug the other end into your Pebble HF.** Make sure the pinout is lined up in the correct orientation before connecting — double-check the pin labels match on both sides.
3. **Drag and drop your firmware file** (a `.hex` file) onto the box on the page, or click the box to browse for it.
4. **Click "Connect & Flash"**, then pick your adapter from the list the browser shows you.
5. Watch the **Writing** and **Verifying** progress bars. When it says it finished successfully, your Pebble HF has the new firmware.

That's it — you don't need to change any of the advanced options.

## Where to get firmware

This updater is meant to program **pre-compiled `.hex` files**. You can download the latest firmware from the releases page:

**https://github.com/mspiceland/usdx-pebblehf/releases**

Download the `.hex` file from a release, then use it in step 3 above.
