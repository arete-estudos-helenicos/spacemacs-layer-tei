# Spacemacs TEI Layer

This is a Spacemacs layer for working with TEI (Text Encoding Initiative) XML files. It includes features for hiding XML tags.

## Installation

1. Clone this repository to your Spacemacs private layers directory (usually `~/.emacs.d/private/`):

   ```sh
   git clone https://github.com/arete-estudos-helenicos/spacemacs-tei-layer.git ~/.emacs.d/private/tei
   ```

2. Add `tei` to the list of layers in your Spacemacs configuration (`~/.spacemacs`):

   ```emacs-lisp
   dotspacemacs-configuration-layers
   '(
     tei
     )
   ```

3. Restart Spacemacs or reload the configuration (`SPC f e R`) for the changes to take effect.

## Features

- **XML Tag Hiding:** Use `SPC x h` to hide XML tags in the buffer, displaying only the text contents enclosed in the tags.

