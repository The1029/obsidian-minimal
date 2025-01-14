---
permalink: features/block-width
cssclasses:
  - table-col-1-200
  - table-full
---

#features

# Overview

Block width allows you to define the width per block type. [[Tables]], [[images]], and [[iframes]] can flow outside of the normal text [[Line width|line width]], to fill more space within a pane. 

Block width requires "Readable line length" to be turned on in Obsidian Settings → Editor.

You can choose width options per block type, and per note. In the future [[Dataview]] may add the ability to do so on a per table basis. (See [Dataview issue #675](https://github.com/blacksmithgu/obsidian-dataview/issues/675))

Block layout also makes it much easier to navigate wide tables on your mobile devices. Tables scroll horizontally independent of the body text, so it doesn't cause your whole note to shift, nor does it squeeze table contents into unreadably narrow columns.

# Demo

This example shows cycling between table width options using [[Hotkeys]]

![](https://user-images.githubusercontent.com/10565871/147195354-51ed225b-7d25-4fbc-8483-4bb978e2fdf2.gif)

# Line width settings

The following [[Line width]] preferences can be set using [[Minimal Theme Settings]]:

- **Normal line width:** the width of a normal line of text (default 40em)
- **Wide line width:** the width for "wide" elements (default 50em)
- **Maximum line width:** the maximum percentage of width that content can fill inside of a pane (default 88%)

# Helper classes

The following [[Helper classes]] can be used to force the width of blocks within a specific note:

| Class                                   | Description                            |
| --------------------------------------- | -------------------------------------- |
| `wide`                                  | Entire note uses wide line width       |
| `max`                                   | Entire note uses max line width        |
| `table-wide`, `img-wide`, `iframe-wide` | Block type uses wide line width        |
| `table-max`, `img-max`, `iframe-max`    | Block type uses max line width         |
| `table-100`, `img-100`, `iframe-100`    | Block type uses 100% of the pane width |

# Hotkeys

- Cycle between image width options
- Cycle between table width options
- Cycle between iframe width options

# Developers

You can visualize the block width settings by using the command palette (`CMD + P`) and turning on the `Minimal Theme Settings: Show block widths` toggle.

![](https://camo.githubusercontent.com/ecc45faa61bb01128193dfd44a4519611f084bba13da081dd68c4f79d7ae2552/68747470733a2f2f6b65702d6c6f672e73332d75732d776573742d322e616d617a6f6e6177732e636f6d2f6d696e696d616c2d646576746f6f6c732d6578616d706c652e706e67#interface)