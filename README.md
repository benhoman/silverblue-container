# Silverblue

My Silverblue boot container.

## Changes to Base Silverblue

### Sway

It's the best window manager, so I layer it, plus most of the bits and bobs that you need to make it delightful. Also, I stole the launcher script from the Fedora Sway spin.

### Firefox

The Fedora version is removed (use the Flatpak version instead).

## Usage

Warning: This is an experimental feature and should not be used in production (yet), (however it's pretty close). Depending on the version of rpm-ostree on your system you might need to pass an additional `--experimental` flag

To rebase an existing Silverblue/Kinoite machine to the latest release: 

    sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/benhoman/silverblue:latest
