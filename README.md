# OLKB Planck rev4/5 alternate bottom row

as it turns out, rev5 and before have a different bottom row layout that isn't supported in any firmware or QMK (as far as i know). i've only verified this on rev4 and rev5, as those were the only ones i could get. going by Planck pictures on [wilba dot tech](https://wilba.tech/planck), it looks like rev1 might support it as well.

that layout is: 1.25/1.25/1.25/1.75/1/1.75/1.25/1.25/1.25

![Planck rev4 with alternate bottom row](https://github.com/sbkeebs/planck-alt-row/blob/main/images/planck_rev4_widemods.jpg)

since this layout isn't present in QMK, this repo contains the keyboard.json files that can be used to add this layout. it's called `LAYOUT_planck_widemods`. you can replace the `qmk_firmware/keyboards/planck/rev4/keyboard.json` file (replace rev4 with your revision) in your own local qmk_firmware with this one, change your keymap to use this layout and add a bottom row with 9 keys.

also, this repo contains a 3d-printable STEP and STL file for the case-compatible plate that i whipped up to support this layout, since the included plate definitely won't.

### todo:
- upload a photo for here
- upload plate files
- write a vial.json that includes this layout
