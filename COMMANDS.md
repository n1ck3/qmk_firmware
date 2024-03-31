# Commands to build

Run `make [keyboard_path]:[keymap] -e CONVERT_TO=promicro_rp2040

- The path to the keyboard relative to "QMK_ROOT_DIR/keyboards"
- CONVERT_TO is important for the make process to build for the right type of micro controller.

E.g.
```bash
make nicke/aurora/lily58/rev1:via -e CONVERT_TO=promicro_rp2040
make nicke/corne/rev1:via -e CONVERT_TO=promicro_rp2040
make nicke/planck_revolution:via -e CONVERT_TO=promicro_rp2040
```
