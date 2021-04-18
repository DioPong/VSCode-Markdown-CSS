# VSCode Markdown Style

You can custom you VSCode markdown css style. Here is my simple style.

## Themes

- [github.css](<https://cdn.jsdelivr.net/gh/DioPong/VSCODE-MARKDOWN-CSS@main/scheme/github.css>)

- [light-default.css](<https://cdn.jsdelivr.net/gh/DioPong/VSCODE-MARKDOWN-CSS@main/scheme/light-default.css>)

- [dark-default.css](<https://cdn.jsdelivr.net/gh/DioPong/VSCODE-MARKDOWN-CSS@main/scheme/dark-default.css>)

- Updating more themes...

## Usage

1. Copy links above (or copy github raw css file in /scheme/xxx.css).

1. Open VSCode's `settings.json`

   > Press `Ctrl + Shift + P` on Windows. Input `settings.json` and open it.

1. Append JSON snippet below:

   ```JSON
   "markdown.styles": [
        "/path/to/style.css" 
    ]
   ```

   Attention: `/path/to/style.css` Can be remote or local CSS file.

   > If you are using both Light/Dark VSCode theme. JSON snippet should be like this:
   >
   > ```JSON
   >  "markdown.styles": [
   >   "/path/to/light-default.css",
   >   "/path/to/dark-default.css"
   > ]
   > ```

## License

Licensed under the [MIT](<https://github.com/DioPong/VSCode-Markdown-CSS/blob/main/LICENSE>) License.

## Thanks

<https://github.com/raycon/vscode-markdown-style>
