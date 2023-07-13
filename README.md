# bufferline.lua
A fast bufferline based on nvchad's tabufline

## Install

### Packer

```lua
use {
    "nvoid-lua/bufferline.lua",
    requires = 'nvim-tree/nvim-web-devicons',
    config = function
        require("bufferline").setup({ kind_icons = true })
    end,
}
```

### Lazy

```lua
{
    "nvoid-lua/bufferline.lua",
    dependencies = 'nvim-tree/nvim-web-devicons',
    config = function
        require("bufferline").setup({ kind_icons = true })
    end,
}
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
