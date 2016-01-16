# James' Karabiner Config Files Collection

Prebuilt, device-specific Karabiner config files to enable every button on your mouse, touchpad or keyboard on OS X, even when no driver available.

## Prerequisite

Download and install Karabiner from [here](https://pqrs.org/osx/karabiner/).

## Quick Installation

Paste the following line in a terminal and press enter.

```shell
cd ~/Library/Application\ Support/Karabiner/ && git clone https://github.com/Jamesits/james-karabiner-config.git
```

Then edit `~/Library/Application\ Support/Karabiner/private.xml` to be like this:

```xml
<?xml version="1.0"?>
<root>
    <include once="true" path="james-karabiner-config/all.xml"/> <!-- put this line directly under <root>! -->
</root>
```

Finally, open Karabiner preference and click the "Reload XML" button under "Change Key" tab. Some new options will show up on the top of the list.

## Update

```shell
cd ~/Library/Application\ Support/Karabiner/ && git pull
```

## Supported Devices List

 * [Dell TP713 Wireless Trackpad](http://www.dell.com/support/home/us/en/04/product-support/product/dell-tp713-wireless-touchpad/research)
 * [Microsoft Sculpt Comfort Mouse](https://www.microsoft.com/accessories/en-us/products/mice/sculpt-comfort-mouse/h3s-00003)

Contributions welcomed.

## Maintainer

 * [James Swineson](https://swineson.me)
