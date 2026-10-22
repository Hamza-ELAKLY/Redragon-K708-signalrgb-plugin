<p align="center">
  <a href="https://signalrgb.com"><img src="https://signalrgb.com/assets/signalrgb-logo-mnml.svg" alt="SignalRGB" height="60"></a>
</p>

<h1 align="center">Redragon K708 Pro for SignalRGB</h1>

<p align="center">
  <a href="https://signalrgb.com">SignalRGB</a> ·
  <a href="https://hamza-elakly.github.io/Redragon-K708-signalrgb-plugin/tools/key-check.html">Key Check</a>
</p>

<p align="center">
  <img src="https://cdn.shopify.com/s/files/1/0655/1289/8735/files/K708-F4.png?v=1735965955&crop=region&crop_left=113&crop_top=446&crop_width=1376&crop_height=588&width=1000" alt="Redragon K708 Pro keyboard" width="700">
</p>

<table align="center">
  <tr>
    <td align="center"><a href="https://redragon.com/products/redragon-k708ak-rgb-pro-mechanical-keyboard"><img src="https://cdn.shopify.com/s/files/1/0655/1289/8735/files/Redragon_K708AK-RGB-PRO_TKL_Mechanical_Keyboard_Software_Download.png?v=1786945839&crop=region&crop_left=74&crop_top=346&crop_width=1114&crop_height=486&width=600" alt="K708AK Anime" width="250"></a><br><sub>K708AK · Anime</sub></td>
    <td align="center"><a href="https://redragon.com/products/redragon-k708gg-rgb-pro-mechanical-keyboard"><img src="https://cdn.shopify.com/s/files/1/0655/1289/8735/files/Redragon_K708GG-RGB-PRO_Mechanical_Keyboard.png?v=1745308416&crop=region&crop_left=124&crop_top=452&crop_width=1344&crop_height=580&width=600" alt="K708GG Gradient" width="250"></a><br><sub>K708GG · Gradient</sub></td>
    <td align="center"><a href="https://redragon.com/products/redragon-k708mc-rgb-pro-tkl-mechanical-keyboard"><img src="https://cdn.shopify.com/s/files/1/0655/1289/8735/files/Redragon_K708MC_RGB_PRO_TKL_Mechanical_Keyboard_Software_Download.png?v=1786945855&crop=region&crop_left=112&crop_top=440&crop_width=1376&crop_height=592&width=600" alt="K708MC Black and White" width="250"></a><br><sub>K708MC · Black &amp; White</sub></td>
  </tr>
  <tr>
    <td align="center"><a href="https://redragon.com/products/redragon-k708gf-rgb-pro-tkl-mechanical-keyboard"><img src="https://cdn.shopify.com/s/files/1/0655/1289/8735/files/K708GF-RGB-PRO_8303e6ea-f0dc-462e-bbd9-7e1afbccb924.png?v=1750156275&crop=region&crop_left=100&crop_top=436&crop_width=1420&crop_height=604&width=600" alt="K708GF Cartoon" width="250"></a><br><sub>K708GF · Cartoon</sub></td>
    <td align="center"><a href="https://redragon.com/products/redragon-k708wlg-rgb-pro-tkl-mechanical-keyboard"><img src="https://cdn.shopify.com/s/files/1/0655/1289/8735/files/K708WGL_TKL.png?v=1757648788&crop=region&crop_left=108&crop_top=440&crop_width=1376&crop_height=592&width=600" alt="K708WLG White" width="250"></a><br><sub>K708WLG · White</sub></td>
    <td align="center"><a href="https://redragon.com/products/redragon-k708-rgb-pro-gasket-mechanical-keyboard"><img src="https://cdn.shopify.com/s/files/1/0655/1289/8735/files/K708-F4.png?v=1735965955&crop=region&crop_left=113&crop_top=446&crop_width=1376&crop_height=588&width=600" alt="K708 Black" width="250"></a><br><sub>K708 · Black</sub></td>
  </tr>
</table>

<p align="center"><sub>All six versions are the same keyboard inside; only the colors and keycaps change, so this plugin should work on all of them (<a href="https://fccid.io/TUVET-7156B/Letter/FCC-MODEL-DIFFERENCE-LETTER-8314657">FCC filing</a>).</sub></p>

SignalRGB doesn't detect the Redragon K708 Pro (the LCD one). It turns out it uses the same EVision chip as some Redragon keyboards SignalRGB already supports, so I made a plugin for it.

## What works

- Per-key RGB, synced with your SignalRGB effects
- All 81 keys light up in the right place

## Good to know

- Works over the **USB cable** and the **2.4G dongle**. Bluetooth isn't supported.
- Over the dongle, the keyboard may use a bit more battery since the lights update constantly.
- The **screen** and **knob** keep working as normal, but SignalRGB doesn't control them.

## How to install

1. Download **[Redragon_K708_Pro.js](https://github.com/Hamza-ELAKLY/Redragon-K708-signalrgb-plugin/releases/latest/download/Redragon_K708_Pro.js)** from the latest release.
2. Put it in this folder:
   ```
   Documents\WhirlwindFX\Plugins
   ```
3. Close Redragon's own keyboard software if it's open.
4. Connect your keyboard with the USB cable or the 2.4G dongle.
5. Fully close SignalRGB (right-click its tray icon → Exit), then open it again.

Your keyboard now shows up in SignalRGB as **Redragon K708 Pro**.

## How to remove

Delete the file from the `Plugins` folder and restart SignalRGB. Nothing on your keyboard is changed.

## Tested on

- Redragon K708AK-RGB-PRO (Flekact Pro, anime version), USB cable and 2.4G dongle
- [SignalRGB](https://signalrgb.com) 2.5.80
- Windows 10

The other versions (K708, K708GG, K708MC, K708GF, K708WLG) have the same internals, so they should work the same way. If you have one, [let me know if it works](https://github.com/Hamza-ELAKLY/Redragon-K708-signalrgb-plugin/issues/new?template=works_on_my_keyboard.yml).

## Test your keys

I made a **[Key Check page](https://hamza-elakly.github.io/Redragon-K708-signalrgb-plugin/tools/key-check.html)** while testing this. Open it in your browser: it shows each key as you press it and flags any key that types twice. Try it once with SignalRGB closed and once with it running to compare.

## Contributing

Found a problem? [Open an issue](https://github.com/Hamza-ELAKLY/Redragon-K708-signalrgb-plugin/issues/new/choose). Want to improve the plugin? Pull requests are welcome, see [CONTRIBUTING.md](CONTRIBUTING.md).

---

<sub>Not affiliated with Redragon or SignalRGB. Built on SignalRGB's EVision plugin by WhirlwindFx & Nuonuo. See [LICENSE](LICENSE).</sub>
