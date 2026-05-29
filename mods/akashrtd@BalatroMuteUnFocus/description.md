# BalatroMuteUnFocus

A lightweight Balatro mod that mutes all audio when the game window loses focus and restores it when you switch back.

## Features

- Mutes audio on alt-tab / focus loss
- Restores previous volume on focus regain
- Zero configuration — install and play
- No Steamodded dependency — works with Lovely only
- Compatible with all other mods

## Requirements

- [Lovely](https://github.com/ethangreen-dev/lovely-injector) (mod loader)

## How It Works

Uses Lovely to inject a `love.focus(f)` callback into Balatro's `main.lua` that calls `love.audio.setVolume(0)` on focus loss and restores the saved volume on focus regain.

## Uninstalling

Delete the `BalatroMuteUnFocus` folder from your Mods directory.

## License

The MIT License (MIT)
Copyright © 2026 akashrtd

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
