# Codex Waifu Pets

A collection of chibi pixel-art pets for ChatGPT Desktop and Codex. Each package contains a pet manifest and a transparent sprite sheet with 57 frames across nine animation states. The packages were tested with the Codex terminal pet picker.

| Pet | Description | Animation sheet |
| --- | --- | --- |
| [Kuroha](packages/kuroha-terminal.tar.gz) | Kuroha Tsukishiro, a half-elf, half-wolf researcher at Tsukikage Observatory. | [Preview](previews/kuroha.png) |
| [Reiko](packages/reiko-terminal.tar.gz) | Reiko Hiramoto, with a pink hoodie, sky-blue hair accents, and a bistable-trap hairpin. | [Preview](previews/reiko.png) |
| [Holo](packages/holo-terminal.tar.gz) | Holo the Wise Wolf from *Spice and Wolf*, in her blue traveling blouse and red sash. | [Preview](previews/holo.png) |
| [Myuri](packages/myuri-terminal.tar.gz) | Holo’s daughter from *Wolf & Parchment*, with silver wolf ears, a pale tail, and a relaxed idle pose. | [Preview](previews/myuri.png) |

## Install

Download a package, then extract it into its own folder under `~/.codex/pets/`. For example, from the directory containing the downloaded Myuri archive:

```sh
pet_dir="${CODEX_HOME:-$HOME/.codex}/pets/myuri"
mkdir -p "$pet_dir"
tar -xzf myuri-terminal.tar.gz -C "$pet_dir"
```

In an interactive Codex session, open `/pets` or select her directly with `/pets myuri`. For desktop setup and terminal requirements, see the [Pets guide](https://learn.chatgpt.com/docs/pets).

## AI usage disclaimer

These sprites were made with generative AI. Official character reference sheets were provided where available, along with character sheets for the original characters. A GPT-Sol model used those sheets as visual references and directed ImageGen to create the pixel-art base sprites and individual animation frames. The generated frames were then assembled and checked with the pet tooling.

Kuroha and Reiko are original characters. Holo and Myuri are unofficial fan sprites based on *Spice and Wolf* and *Wolf & Parchment*, respectively.
