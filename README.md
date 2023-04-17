# Marp CLI example

view life:
https://s-light.github.io/marp_test/

-   based on https://open.vscode.dev/yhatt/marp-cli-example
-   Write your slide deck by [Marp] Markdown.

[marp]: https://marp.app/

## How to write

For Marp slide deck features, please see the documentation of [Marpit Markdown](https://marpit.marp.app/markdown), [the features of Marp Core](https://github.com/marp-team/marp-core#features), and the default example in [`PITCHME.md`](https://raw.githubusercontent.com/yhatt/marp-cli-example/master/PITCHME.md) for .

### Edit deck

Just edit **[`PITCHME.md`](./PITCHME.md)**!

#### Preview deck

**[Marp for VS Code]** extension is the best partner for writing Marp slide deck with live preview.

<p align="center">
  <a href="https://open-vsx.org/extension/marp-team/marp-vscode">
    <img src="https://raw.githubusercontent.com/marp-team/marp-vscode/master/docs/screenshot.png" width="500" />
  </a>
</p>

**You can try edit and preview on the web now!** Open https://github.dev/yhatt/marp-cli-example/blob/master/PITCHME.md or hit <kbd>.</kbd> key on this repository, and install [Marp for VS Code] extension.

[marp for vs code]: https://open-vsx.org/extension/marp-team/marp-vscode

### Assets and themes

-   `assets` directory can put your assets for using in the deck. (e.g. Image resources)
-   `themes` directory can put [custom theme CSS](https://marpit.marp.app/theme-css). To use in the deck, please change `theme` global directive.
