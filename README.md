# matrix.nvim

Theme for Neovim inspired by the "Matrix" saga

## Installation

- lazy.nvim

  ```lua
  return {
      "xxyrnn/matrix.nvim",
      lazy = false,
      priority = 1000,
      config = function()
          vim.cmd.colorscheme("matrix")
      end
  }
  ```
