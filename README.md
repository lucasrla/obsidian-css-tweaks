[CSS snippet](https://forum.obsidian.md/t/obsidian-release-v0-9-18-insider-build/9063) with minimal tweaks and fixes to [Obsidian](https://obsidian.md)'s Appearance. I have tested them in versions up to `0.12.4`.

## Overview

Tweaks that I have written myself:

- Cleaner external links: remove the external link image (<?xml version="1.0" encoding="utf-8"?><svg xmlns='http://www.w3.org/2000/svg' class='i-external' viewBox='0 0 32 32' width='14' height='14' fill='none' stroke='#888888' stroke-linecap='round' stroke-linejoin='round' stroke-width='9.38%'><path d='M14 9 L3 9 3 29 23 29 23 18 M18 4 L28 4 28 14 M28 4 L14 18'/></svg>)
- Cleaner blockquotes: a vertical line instead of a closed box
- Cleaner embeds: no margins, no borders, just some padding
- Alternative way to distinguish internal vs external links: remove underline from internal links
- Alternative coloring for the `<mark>` tag both in light and dark themes

Features that I have gotten from others:

- [Good-looking checkboxes](https://forum.obsidian.md/t/nicer-checkboxes/2238)
- [Pills for tags](https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/13)
- [On/off auto fading for UI controls](https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/10)
- [Cleaner embeds by removing YAML's front matter](https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/41)

## Setup

1. Copy the `obsidian-minimal-tweaks.css` file to `VAULT_DIRECTORY/.obsidian/snippets/`
2. Open the Obsidian app
3. Navigate to `Settings` > `Appearance` > `CSS snippets` and toggle `obsidian-minimal-tweaks` to ON

If there is no `obsidian-minimal-tweaks` in step #3, you might need to click on the button that `Reload snippets`.

## More resources

If you are looking for more CSS snippets, check out this [forum thread](https://forum.obsidian.md/t/meta-post-common-css-hacks) and also [@kmaasrud/awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian). Thanks, Obsidian community!