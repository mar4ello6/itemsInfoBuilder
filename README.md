# GT's items.dat decoder
It decodes all items from items.dat and gets all items' descriptions and item mods from [GT Wiki](https://growtopia.fandom.com/wiki/). It outputs JSON file.

For lazy people, who doesn't see Releases tab: [Download latest items.json](https://github.com/mar4ello6/itemsInfoBuilder/releases/download/latest/items.json)

Parser is compiled for use on Linux. Compiling it using g++ (check [this](../main/source/build.sh) to see the compiling command). It uses:
* [GrowtopiaNoobs' items.dat decoder](https://github.com/GrowtopiaNoobs/Growtopia_ItemsDecoder) as base
* [cpp-httplib](https://github.com/yhirose/cpp-httplib) to get descriptions and mods from wiki
* [JSON](https://github.com/nlohmann/json) to store got items' data

Also, when I (or you in fork/pull request) upload new items.dat to repository, it automatically releases new items.json, so you don't need to run parser on your machine everytime.

Originally made for GTace, but everyone can use it now.
