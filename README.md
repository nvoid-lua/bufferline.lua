# bufferline.lua
![bufferline](https://github.com/nvoid-lua/bufferline.lua/assets/94284073/d090e833-7b74-43c3-8ff4-ba91c51b65f9)

A fast bufferline based on nvchad's tabufline

## Install

### Packer

```lua
use {
    "nvoid-lua/bufferline.lua",
    requires = 'nvim-tree/nvim-web-devicons',
    config = function()
        require("bufferline").setup({ kind_icons = true })
    end,
},
```

### Lazy

```lua
{
    "nvoid-lua/bufferline.lua",
    dependencies = 'nvim-tree/nvim-web-devicons',
    config = function()
        require("bufferline").setup({ kind_icons = true })
    end,
},
```

## Setup

```lua
require("bufferline").setup {
  always_show = false,
  show_numbers = false,
  kind_icons = true,
  icons = {
    unknown_file = "󰈚",
    close = "󰅖",
    modified = "",
    tab = "󰌒",
    tab_close = "󰅙",
    tab_toggle = "",
    tab_add = "",
  },
}
```

## Highlights

```
TblineFill
TbLineBufOn
TbLineBufOff
TbLineBufOnModified
TbBufLineBufOffModified
TbLineBufOnClose
TbLineBufOffClose
TblineTabNewBtn
TbLineTabOn
TbLineTabOff
TbLineTabCloseBtn
TBTabTitle
TbLineCloseAllBufsBtn
```
