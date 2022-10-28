My opinionated tweaks to [Obsidian](https://obsidian.md)'s theme, [Minimal](https://github.com/kepano/obsidian-minimal) by [kepano](https://github.com/kepano).

I'm using these [CSS snippets](https://help.obsidian.md/How+to/Add+custom+styles#Use+Themes+and+or+CSS+snippets) in Obsidian `1.0.3` with Minimal theme `6.1.9`.


## List of tweaks

- Text font: "Helvetica Neue" as primary text font
- Line height: increase it slightly (from 1.5 to 1.6)
- Embeds: wider; no borders, just some padding and vertical space for the title
- Highlights: alternative background color both in light and dark themes
- Blockquotes: subtler left border, alternative text color, increased margins
- External links: remove the SVG image (<img src="https://user-images.githubusercontent.com/1920195/198417807-298c819e-35a7-45de-9da8-de4caac7a9e2.svg">)
- Internal links: remove underline (to make them distinguishable from external links)
- Horizontal rule (`<hr>`): just three subtle dots, instead of a thick and wide line
- Footnotes: more vertical space between items, more left space between footnote content and the backref link (↩︎)


## Setup

1. Copy the `obsidian-minimal-tweaks.css` file to `VAULT_DIRECTORY/.obsidian/snippets/`
2. Open the Obsidian app
3. Navigate to `Settings` > `Appearance` > `CSS snippets` and toggle `obsidian-minimal-tweaks` to ON

If there is no `obsidian-minimal-tweaks` in step #3, you might need to click on the "refresh" button to `Reload snippets`.


## More resources

If you are looking for more CSS snippets, check out this [forum thread](https://forum.obsidian.md/t/meta-post-common-css-hacks) and also [@kmaasrud/awesome-obsidian](https://github.com/kmaasrud/awesome-obsidian). Thanks, Obsidian community!