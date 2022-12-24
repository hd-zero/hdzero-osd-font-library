# hdzero-osd-font-library

Share the osd font library you made or get your favorite.

# How to get and use the osd font you need

- Select a font file (`*.bmp`) you like in the folder according to FC VARIANT.For betaflight, the corresponding folder name is `BTFL`.
- Copy `*.bmp` to SDCard and rename it.
  - For hdzero goggle:
    - You need to confirm that the FW version is >= **7.66.120**.
    - copy `*.bmp` to your sd card, the path is `resource/OSD/FC/`, if the path does not exist, please create it.
    - Renamed `*.bmp` to `FC_VARIANT_000.bmp`. For betaflight, the corresponding file name is `BTFL_000.bmp`.
  - For sharkbyte vrx:
    - You need to confirm that the FW version is **40.8F.4E**.
    - copy `*.bmp` to your sd card, the path is `Resource/`, if the path does not exist, please create it.
    - Renamed `*.bmp` to `FC_VARIANT.bmp`. For betaflight, the corresponding file name is `BTFL.bmp`.
  - For hdzero vrx4:
    - You need to confirm that the FW version is **xx.xx.xx**.
    - copy `*.bmp` to your sd card, the path is `Resource/`, if the path does not exist, please create it.
    - Renamed `*.bmp` to `FC_VARIANT.bmp`. For betaflight, the corresponding file name is `BTFL.bmp`.

# How to upload your custom osd font

- font file format:

  - .bmp format, 24bit color
  - Font size is 24x36
  - Font spacing of 0 or 6 pixels
  - if(r,g,b)==(127,127,127). Pixels are transparent.
- Font file naming rules:
  In order to avoid file name conflicts as much as possible, the naming rules are as follows:
  "FC_VARIANT" _ "username" _ "style" _ "version" .bmp
  Such as BTFL_ligen_colorful_v1.0.0.bmp
- PR rules:
  Please show a picture of it working correctly when submitting a PR.
