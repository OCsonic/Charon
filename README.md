# Tools
## Asphodel
Displays PCI information relating to all connected GPUs and lists the most recently loaded xorg modules for each.

This is primarily for verifying the installation of modules for each GPU to help quickly figure out if there's an obvious problem.

## Elysium
Allows you to switch between connected graphics cards both on Xorg and Wayland.

| Driver Support Status |
| --- | ----: |
| Nvidia (Proprietary) | ☑️ |
| Nvidia (Nouveau) | ☑️ |
| Radeon | ❔[^1] |
| Intel (Integrated) | ☑️ |
| Other | ❌ |
[^1]: There is an attempt to provide AMD GPU support but it's completely untested as I dont have the hardware.

## Tartarus
Displays which graphical APIs are working on the current GPU and provides basic info like the name of the driver, the detected GPU name, aswell as the supported versions of various graphical APIs.