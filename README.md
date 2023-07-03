
## New Steps:

https://docs.qmk.fm/#/newbs_getting_started

1. git clone qmk 
2. git submodule init
3. git submodule update
4. download the layout.json 
5. plug the keyboard in directly, not through the usb hub
6. flash both halves
7. `qmk flash redox.json`
 
## Old Steps

### First time:

1. Go to https://config.qmk.fm/#/redox/rev1/LAYOUT
2. Update layout
3. Download full source
4. Unzip to repo
5. `bin/qmk compile redox-rev1-layout_mine.json`
6. `cp keyboards/redox/keymaps/{default/config.h,layout_mine/}`
7. `bin/qmk flash redox-rev1-layout_mine.json` 

numlock: https://github.com/qmk/qmk_firmware/issues/2164

### Afterwards:

1. Go to https://config.qmk.fm/#/redox/rev1/LAYOUT
2. Upload `qmk_firmware/redox-rev1-layout_mine.json`
3. Update layout
4. Download full source
5. Unzip to repo
6. Verify the changes
7. `bin/qmk flash redox-rev1-layout_mine.json` 
