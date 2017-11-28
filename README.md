# grok-link README

Produces grok url links from the current line and file, such as:

`https://my-grok-server/source/xref/my-project/my-file#1234`

## Features

Uses a configuration option to set the url prefix for a project.

## Requirements

None

## Extension Settings

Set `opengrok.url` to the url prefix you want.


Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something

## Known Issues

None known.

## Release Notes

### 1.0.0

Initial release.
