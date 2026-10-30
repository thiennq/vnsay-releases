# vnsay-releases

Prebuilt **vnsay** binaries, installers and models: Vietnamese text-to-speech
on the command line, without Python. Like Apple's `say`, with Vietnamese
voices first.

```sh
vnsay model install            # the assistant model, checked by SHA-256
vnsay say "Xin chào." --play
```

- Models are published as GitHub Releases tagged `model-<preset>-<n>`
  (for example `model-assistant-1`); each holds a `manifest.json` with every
  file's size and SHA-256.
- Binaries and installers for macOS, Windows and Linux are published here as
  they become available.

This repository was called `zerotts-releases`; old links redirect here.

## Credits and license

vnsay uses the **ZeroTTS** model and engine by **ZeroWeight AI**
(https://github.com/zeroweight-ai/ZeroTTS), released under the MIT License:

    Copyright (c) 2026 ZeroWeight AI

Every package and model release carries that copyright notice and the full
license text (`LICENSE`), together with the notices of the third-party
components it includes.
