# ShopUI

## Plugin updated and edited to help a server YanyanQt, original fork [TradingInterface](https://github.com/Leonidius20/TradingInterface) 

## Features:
-   Buying and selling items & shop management through an intuitive interface;
-   Support for items with enchantments, custom names & lores;
-   The list of items, available for buying, is divided into categories for convenience;
-   Temporary discounts for items (which expire after a set time);
-   Custom translations of items' names (for displaying in the shop).

## Installation:
-   Make sure that [EconomyAPI][economy] and [DbLib][dblib] are installed on your server;
-   Place the plugin's _.jar_ file into _plugins_ folder on your server;
-   Launch the server and set up the plugin through its interface.

## Setting up:
Shop management functions are available for players with `shop.edit` permission (operators have it by default). Players with this permission will see management buttons in the interface.

## Usage:
To open up the shop's interface type `/shop` into the chat.

## Translations
If the plugin is not translated into the language of your choosing, a file called `<your_lang>.lng`, where `<your_lang>` is the three-letter ID of your language, will be created in the plugin's data folder. It will contain text strings in the format of `key: value`, where `key` is the string's identifier and `value` is the string itself. Replace values in English with the values in your language, and these new strings will be used by the plugin. You can also start a pull request, placing `<your_lang>.lng` into `src/main/resources/lang`, and your translation may officially become a part of the plugin.

## Building from sources
`mvn clean package`

## Links
-   [Trading Interface on nukkitx.com](https://nukkitx.com/resources/trading-interface.113/)
-   [Trading Interface on nukkit.ru](http://forums.voxelwind.com/resources/trading-interface.144/)

[economy]: https://github.com/EconomyS/EconomyAPI
[dblib]: https://github.com/fromgate/DbLib
[nukkitx]: http://github.com/NukkitX/Nukkit
