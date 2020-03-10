# Kapitonov Plugins Pack (KPP) - headless build for ELk Pi

Modified for headless plugin build for [Elk Audio OS](https://elk.audio).

Amplifier plugin currently not supported due to the dependency on zita-convolver.

## Building Instructions

Follow original build instructions setting up these configuration variables before building:
```bash
$ meson build --reconfigure -Dladspa=disabled -Dgui=disabled
```

