# dotfile

## .spacemacs

Configuration file for [spacemacs](https://spacemacs.org), should be placed in `~/` directory.

### Customization

`dotspacemacs-configuration-layers` block changed:

- add `lsp` and `java` layers
  - `lsp` is language server for java, but `meghanada` is specified as language server in `java` configuration for support to gradle build tool
- add `yaml` layers
  - support for yaml files
