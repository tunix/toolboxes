# toolboxes

Stores code for building an OCI images to use with toolbox

## Images

#### pengutool

My daily driver container for doing all sorts of work such as:

* Rust development
* File editing
* Operating servers & clusters
* Management tasks

#### scanner

A container that only has `simple-scan` for scanning documents. Unfortunetely, this package is not available as flatpak
so I have it ready as a toolbox container which I can start in GNOME Overview.

## Usage

```
$ toolbox create -i ghcr.io/tunix/pengutool pengutool
$ toolbox enter pengutool
```

I assign `Super+T` shortcut to start `wezterm` with the following command:

`toolbox run -c pengutool /usr/bin/fish -l`
