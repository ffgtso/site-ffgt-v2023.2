This repository contains the site configuration for the 4830.org Gluon-based firmware.

This is the `v2023.2.x` branch.

Firmware can be built using `make manifest` or `make sign` if a key for signing the manifest is existing in the home directory at `${HOME}/.gluon-secret-key`.
A single target can be built using:

`make build GLUON_TARGETS=lantiq-xrx200`
