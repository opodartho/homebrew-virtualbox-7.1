# `homebrew-virtualbox-7.1`

This custom Homebrew tap is for installing VirtualBox version 7.1, providing compatibility for users whose systems or projects require this specific, older version.

### Background

This tap was created to provide a compatible version of VirtualBox for use with **Vagrant versions 2.4.2 through 2.4.8**. The Vagrant VirtualBox provider is not compatible with versions beyond 7.1.x, and using a newer version would result in an error. This tap ensures seamless operation by providing the last supported version.

### How to Use

First, add this tap to your local Homebrew installation. This makes the formulas and casks in this repository available to you.

```

brew tap opodartho/virtualbox-7.1

```

Once the tap is added, you can install the VirtualBox 7.1 cask using the following command:

```

brew install --cask opodartho/virtualbox@7.1

```

### Uninstallation

To remove the cask, you can use the standard Homebrew command:

```

brew uninstall --cask opodartho/virtualbox@7.1

```

To remove the tap from your system, use the `untap` command:

```

brew untap opodartho/virtualbox-7.1

```

### License

```

        DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                Version 2, December 2004

Copyright (C) 2004 Sam Hocevar [sam@hocevar.net](mailto:sam@hocevar.net)

Everyone is permitted to copy and distribute verbatim or modified
copies of this license document, and changing it is allowed as long
as the name is changed.

        DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE


TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

0.  You just DO WHAT THE FUCK YOU WANT TO.

```
