# Marso Library: Isaac Sim extension registry

The registry for **Marso Library**, the Marso add-on for NVIDIA Isaac Sim. It browses your Marso projects, downloads their
PBR assets as USD and adds them to the stage, creates assets, and films them in Sim Studio.

Registry URL (Isaac Sim 6.0 and later):

```
https://mxr-software.github.io/marso-isaacsim-registry
```

## Install

1. In Isaac Sim, open **Window > Extensions**.
2. Open the menu next to the search box (the gear), choose **Registries**, and add the URL above.
3. Search for **Marso Library**, install it, switch it on (and **Autoload** if you want it every time).
4. Open **Window > Marso Library**, and paste your Marso API key in **Settings** (or set `MARSO_API_KEY`).

From a command line, add `--/exts/omni.kit.registry.nucleus/registries/N/url=https://mxr-software.github.io/marso-isaacsim-registry`
(N: the next free slot) and `--enable marso.library`.

This repository only holds the published files (`v2/`), written by Kit's publisher. Do not edit them by hand.
Issues and questions: contact M-XR at https://m-xr.com.
