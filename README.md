# karabiner-input-switch

## What

A [Karabiner](https://github.com/pqrs-org/Karabiner-Elements) config to remap input language switch hotkey to Alt+Shift.

## Why

### `shift-alt.json`

The default hotkey combination (Ctrl+Space) is nice, however it conflicts with suggestion hotkey at VS Code. To fix this, I decided to remap language switching to Alt+Shift, but macOS doesn't support that out of the box, and, long story short, I ended up with this setup.

I haven't been able to come up with a better hotkey for suggestion prompt, and I'm switching platforms (to Linux and Windows) a lot. This solution works better than any alternatives I've tried.

### `fn.json`

Because Apple can't simply make the Globe key switch inputs. It shows some slow
UI, using which is a **terrible** experience.

## How

1. Install [Karabiner](https://github.com/pqrs-org/Karabiner-Elements).
2. Copy `shift-alt.json` and `fn.json` to the `~/.config/karabiner/assets/complex_modifications/`.
3. Start Karabiner and enable the config.
4. Go to the system input settings of the macOS and rebind the input switch to whatever pressing the `Alt+Shift` or the `Globe/Fn` key emit.
