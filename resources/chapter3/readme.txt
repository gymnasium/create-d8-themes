// File: ecoscribble.info.yml
name: EcoScribble
type: theme
description: A custom theme for the awesomeness which is EcoScribble.
core: 8.x
base theme: stable
version: 8.x-1.0
libraries:
  - ecoscribble/global-styling
regions:
  header: Header
  content: Content
  footer: Footer



// File: ecoscribble.libraries.yml
global-styling:
  version: 1.x
  css:
    theme:
      css/bootstrap.css: {}
      css/custom.css: {}
  js:
    js/bootstrap.js: {}
  dependencies:
    - core/jquery