# Custom Bitwarden Browser Extension

## Prerequisites

- [Taskfile.dev](https://taskfile.dev)

  Should be installed already, but if not `brew install go-task`

- ImageMagick

  Can be installed via Homebrew, just run `task brew`

## How to Build

1) Set the current version in `Taskfile.yml`

    You can obtain this version from the `chrome://extensions/` page with your current extension
2) Set any additional values you wish to change.
2) Run `task build`

## How to install

1) In Chrome navigate to `chrome://extensions/`
2) In the top right, enable "Developer Mode"
3) Select "Load Unpacked" and select the `browser-` folder created.
