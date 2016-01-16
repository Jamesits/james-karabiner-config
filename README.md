# James' Karabiner Config Files Collection

My Karabiner config.

## Devices

 * [Dell TP713 Wireless Trackpad](http://www.dell.com/support/home/us/en/04/product-support/product/dell-tp713-wireless-touchpad/research)

## Quick Installation

```shell
cd ~/Library/Application\ Support/Karabiner/ && git clone https://github.com/Jamesits/james-karabiner-config.git
```

Then modify `~/Library/Application\ Support/Karabiner/private.xml` to be like this:

```xml
<?xml version="1.0"?>
<root>
    <include once="true" path="james-karabiner-config/all.xml"/> <!-- put this line after <root>! -->
</root>
```

Finally, open Karabiner preference and click the "Reload XML" button under "Change Key" tab.

## Update

```shell
cd ~/Library/Application\ Support/Karabiner/ && git pull
```

## Maintainer

 * [James Swineson](https://swineson.me)
