# Dusk theme for Potassium

A sunset theme for the Potassium executor: soft pink accents, an indigo and lavender palette, see-through panels and a 4K dusk wallpaper behind the whole app.

![Potassium with the Dusk theme: Start page and a script tab](window.jpg)

The wallpaper on its own: [`dusk.jpg`](dusk.jpg).

## Loading screen

The theme also replaces Potassium's own loading and login picture with its wallpaper, softly blurred. Potassium's default loading picture (on the right) is the same artwork without the blur.

![Dusk theme loading screen next to Potassium's default](loading-compare.jpg)

## Install

1. In Potassium, open **Settings → Appearance → Custom theme**.
2. Set **Base theme** to **Dark**. The editor's syntax colours come from the base theme.
3. Copy everything in [`Theme.css`](Theme.css) and paste it into **Custom CSS**.
4. Type a name (for example `Dusk`) under **Save** and click **Save**.

## Notes

- The wallpaper loads from `dusk.jpg` in this repo, so you need internet the first time. If the image can't load, the colours still apply.
- Potassium cuts custom CSS off at 50,000 characters. This theme is about 2,000, so there's plenty of room to add your own tweaks.
- The editor and settings-screen rules target Potassium's internal class names. A future Potassium update could rename them; if that happens, the colours keep working but the see-through editor or the solid settings screen may not.
- The wallpaper is "The Valley" by [Louis Coyle](https://louie.co.nz).
