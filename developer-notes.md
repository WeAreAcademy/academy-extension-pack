# Extra notes for developers of this extension

## Docs

Extension Manifest docs:

https://code.visualstudio.com/api/references/extension-manifest#extension-packs

## Dependencies

> An Extension Pack should not have any functional dependencies with its bundled extensions and the bundled extensions should be manageable independent of the pack. If an extension has a dependency on another extension, that dependency should be declared with the extensionDependencies attribute.

Source: https://code.visualstudio.com/api/references/extension-manifest#extension-packs

## Testing from clean

This is an open question.

- The section "Get up and running straight away" mentions using `F5` to open a new window with your extension loaded. - Open `Extensions Viewlet` and check your extensions are installed.

This `F5` is, I think, `Debug: Start Debugging`. It's not clear what context they're suggesting you run this from. Marketplace view? Or with the extension project folder opened in vscode and the file `vsc-extension-quickstart.md` open, say?

- You can load vscode with all extensions disabled: `code --disable-extensions .` but that's not the same as having them appear uninstalled.

## Troubleshooting

`Developer: Show Running Extensions`

## Publishing Extensions

https://code.visualstudio.com/api/working-with-extensions/publishing-extension
