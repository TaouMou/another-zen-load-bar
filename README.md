# Another Zen Load Bar

A thin loading bar along the top edge of the page for [Zen Browser](https://zen-browser.app), plus a mute indicator. CSS only.

- Steps forward as the page loads (15% → 45% → 85% → 95%), driven by the tab's own loading state
- Slides to 100% and fades out when the page finishes
- Uses your Zen theme color, or a custom color
- Full-width colored bar on muted tabs (optional)
- Fits the Glance preview window
- Works in every toolbar layout
- Hides Zen's built-in pulsing pill indicator (optional)

## Install

### With Sine

1. Open the Sine settings in Zen.
2. In the install box, enter:
   ```
   TaouMou/another-zen-load-bar
   ```
3. Click **Install**.

### Without Sine

1. Open `about:support`, find **Profile Folder** and click **Open Folder**.
2. Open the `chrome` folder (create it if it doesn't exist) and paste the contents of [`chrome.css`](chrome.css) into `userChrome.css`.
3. In `about:config`, make sure `toolkit.legacyUserProfileCustomizations.stylesheets` is `true`.
4. Restart Zen.

Without Sine, the settings below stay at their defaults. To change the color or thickness, edit the `:root` block at the top of the CSS.

## Settings

| Setting | Default |
|---|---|
| Use a custom color instead of the Zen theme color | Off |
| Custom color | `#ffffff` |
| Thickness | `3px` |
| Hide the mute indicator | Off |
| Mute indicator color | `orangered` |
| Keep Zen's built-in loading pill as well | Off |

## Credits

Based on [Load Bar](https://github.com/Tanay-Kar/Zen-Themes/tree/main/LoadBar) by [Tanay-Kar](https://github.com/Tanay-Kar). Licensed under GPL-3.0, like the original.
