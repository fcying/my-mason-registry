# :coffee: mason-registry

This project includes some custom lsp that is not available in the main mason-registry.  
some lsp get from [tools](https://github.com/fcying/tools) 

* [clangd with rpath lib](https://github.com/clangd/clangd)
* [autohotkey2-lsp](https://github.com/thqby/vscode-autohotkey2-lsp)

## How to Install

- You can add the new registry before the default mason-registry as follows
- Run `Mason` and wait for mason to update the new registry

```lua
{
  'williamboman/mason.nvim',
  opts = {
    registries = {
      'github:fcying/my-mason-registry',
      'github:mason-org/mason-registry',
    },
  },
}
```
