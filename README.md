# Phaser Editor 2D build scripts for testing

This repository contains the scripts to build the `develop` branch of [Phaser Editor 2D](https://github.com/PhaserEditor2D/PhaserEditor2D-v3).

The `develop` branch contains the new features and bug fixes to be included in the next version of the editor.

Follow these steps:

Setup (just the first time):

```bash
git clone https://github.com/PhaserEditor2D/PhaserEditor2D-v3-build-develop.git
cd PhaserEditor2D-v3-build-develop
npm install
```

Build the latest version (each time you need):

```bash
npm run build
npm run PhaserEditor2D
```

**WARNING!:** When testing the editor, you should clear the browser cache.

This is an alternative to the [Guide for building Phaser Editor 2D step by step](https://github.com/PhaserEditor2D/PhaserEditor2D-v3/blob/develop/BUILD.md).

