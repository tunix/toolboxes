# toolboxes

Stores code for building images to use with toolbox/distrobox

## Images

#### pengutool

My daily driver container for doing all sorts of work such as:

* Rust development
* File editing
* Operating servers & clusters
* Management tasks

## Usage

```
$ toolbox create -i ghcr.io/tunix/pengutool pengutool
$ toolbox enter pengutool
```

I assign `Super+T` shortcut to start `wezterm` with the following command:

`flatpak run org.wezfurlong.wezterm start distrobox enter pengutool -- /usr/bin/fish -l`
