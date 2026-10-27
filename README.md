# Titan Hold Symbols

Hold a letter on the **Unihertz Titan 2 Elite** keyboard to type its symbol.
Tap **S** for `s`, hold **S** until the tick, let go, and you get `4`.
SwiftKey stays your keyboard, and Shift, Alt and fast typing work as usual.

**[⬇ Download the latest APK](https://github.com/jasonlok000/titan-hold-symbols/releases/latest)**

```text
Key:   Q W E R T Y U I O P      A S D F G H J K L      Z X C V B N M
Hold:  0 1 2 3 ( ) _ - + @      * 4 5 6 / : # ' "      7 8 9 ? ! , .
```

You can change any symbol in the app, or empty a box to leave that letter alone.

## Install

1. **Remove the old test version.** If an older Titan Hold Symbols (0.2.x) is installed,
   uninstall it first. The new one is signed with a different key, so it cannot update
   the old one.
2. **Install the APK.** On the phone, open the link above, download
   `TitanHoldSymbols-0.3.0.apk`, and open it. If Android asks, allow your browser to
   install apps.
3. **Install and start Shizuku.** Get Shizuku from Google Play or
   [its GitHub releases](https://github.com/RikkaApps/Shizuku/releases), then start it
   with **Wireless debugging** (Shizuku's app walks you through it). You need to start it
   again after every reboot. Until you do, your keyboard simply works normally.
4. **Connect.** Open Titan Hold Symbols and tap **Authorize / reconnect Shizuku**, then
   **Allow**. It should say `Shizuku: Ready`.
5. **Turn on the accessibility service.** Tap **Open accessibility settings** and turn
   on **Titan Hold Symbols**. If Android says the setting is restricted, go back, tap
   **App info / restricted settings**, open the **⋮** menu, choose
   **Allow restricted settings**, then try again.
6. **Turn off Key Mapper's accessibility service**, if you use Key Mapper.
7. Turn on **Enable hold symbols**, then type in **Try it here**.

## Using it

- Letters appear when you let go of the key, or as soon as you press the next one,
  so fast typing stays in the right order.
- Hold a letter until you feel a small tick, then let go: you get the symbol instead.
  The hold time (default 400 ms) can be changed in the app.
- Shift+letter, Alt+letter, number fields and terminals all stay as they were.
  Password fields are skipped unless you turn them on.
- To switch it off quickly, use the **Hold Symbols** Quick Settings tile, or turn off the
  accessibility service.

## Privacy

There is no Internet permission. The app never reads your text, the screen or the
clipboard, and keeps no history. It re-types the letter or symbol you pressed through
Android's input system, using the Shizuku permission you grant. The diagnostics in the
app are counters only.

## Verify the download

- File: `TitanHoldSymbols-0.3.0.apk`, version 0.3.0 (code 4), package `com.jasonlok.titanhold`
- SHA-256: `0230bd9af661bbb4c787c40fceb6926054e8efefd949332073391a3a7b0ebb65`
- Signing certificate SHA-256: `bb769da3c4aa70bf9e50604df662153998ce64baf410ee0cd3e7579afafa9420`

Requires Android 13 or newer. It was made for the Titan 2 Elite on Android 16, and its
built-in keyboard is the only one used by default.

---

# Scale Toggle

One press switches the Titan 2 Elite between **phone mode** and **tablet mode** (a
roomier, tablet-style layout). It has no screen: it flips the mode, shows `Phone mode`
or `Tablet mode`, and closes.

**It's meant to be bound to a long press of the side button.**

**[⬇ Download ScaleToggle-1.0.4.apk](https://github.com/jasonlok000/titan-hold-symbols/releases/download/scaletoggle-v1.0.4/ScaleToggle-1.0.4.apk)**

## Install

1. **Install the APK.** If you already have Scale Toggle 1.0.2 or 1.0.3, install
   straight over it; don't uninstall first.
2. **Start Shizuku** (same as step 3 above). The first time you open Scale Toggle,
   tap **Allow** when Shizuku asks.
3. **Bind it to the side button.** In the phone's side-button settings, set
   **Long press** to open the app **Scale Toggle**.
4. Long-press the side button: you'll see `Tablet mode`. Long-press again for
   `Phone mode`.

Tablet mode sets the display to exactly 287 DPI, a setting tested on the Titan 2 Elite
with WhatsApp and other apps. Phone mode goes back to the standard size. Only display
density changes: your font size, resolution and rotation settings are left alone.
Some open apps may redraw when you switch.

## Verify the download

- File: `ScaleToggle-1.0.4.apk`, version 1.0.4 (code 5), package `dev.everyonesniche.scaletoggle`
- SHA-256: `0877b844d1979cfaac994ee67cad58371e521ac2dc4e22e2cfa9ad9d4c3b26df`
- Signing certificate SHA-256: `4060aaece81427fb1bf94469296f7a28aa9b8101b645dacf4a2a6f64b26e60b0`

Requires Android 11 or newer and Shizuku. No Internet permission.
