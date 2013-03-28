A Bro language support module for the TextMate editor.

Seth Hall <seth@icir.org>

TextMate Installation
=====

To install, open the bro.tmbundle directory with TextMate
  (e.x. with the "open" command, the "mate" command, or in Finder)

To update your Bro bundle, you can do this
  ```
  cd ~/Library/Application Support/TextMate/Bundles/bro.tmbundle
  git pull
  ```

Sublime 2 Installaion
=====

Sublime 2 supports TextMate bundles, but the directory is named slightly differently. The easiest way is to clone this repo somewhere, and then create a symlink:

```ln -s ~/src/bro.tmbundle ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/Bro```
