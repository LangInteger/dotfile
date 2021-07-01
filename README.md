# dotfile

## .spacemacs

- Step 1: clone spacemacs via `git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d`
- Step 2: make a soft link via `ln -s path/to/this/repo/.spacemacs ~/.spacemacs`

Configuration file for [spacemacs](https://spacemacs.org), should be placed in `~/` directory.

### Customization

`dotspacemacs-configuration-layers` block changed:

- add `lsp` and `java` layers
  - `lsp` is language server for java, but `meghanada` is specified as language server in `java` configuration for support to gradle build tool
- add `yaml` layers
  - support for yaml files
