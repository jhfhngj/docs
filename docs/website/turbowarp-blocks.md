---
slug: /blocks
hide_table_of_contents: false
---

# TurboWarp Blocks

TurboWarp has a section of blocks that allows you to use certain features previously not accessible to Scratch projects.

## is compiled? and is TurboWarp? {#is-compiled}

![is compiled?](./assets/is-compiled.svg)

See https://scratch.mit.edu/projects/414716080/

These blocks are "compatible" with Scratch because they're actually just modified argument reporters.

:::warning
Every block beyond this warning is **incompatible** with Scratch. Projects that using them **can not** be uploaded to the Scratch website. If you don't use any TurboWarp-exclusive blocks, then there should be no issue with making your project in TurboWarp and uploading it to Scratch.

**We do not recommend using these blocks. No new blocks will be added in the forseeable future**.
:::

## last key pressed {#last-key-pressed}

![last key pressed](./assets/last-key-pressed.svg)

It tells you the last key that was pressed. It's intended to be used something like this:
Any key pressed on keyboard and pressed this with mouse would show you the key you
pressed.
## mouse button down? {#mouse button name}

![primary mouse button down?](./assets/mouse-button-down.svg)

It's like "mouse down?" but lets you check each individual button. Keep in mind that due to how Scratch interprets mouse input, it's possible for a block like "is primary mouse button down?" to report true while the standard "mouse down?" reports false.

0. Left
1. Middle as ScrollWheel (on all mouses)
2. Right (right for menu in browsers like MS Edge)
