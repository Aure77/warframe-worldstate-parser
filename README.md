# Warframe Worldstate Parser

[![Supported by Warframe Community Developers](https://raw.githubusercontent.com/Warframe-Community-Developers/banner/master/banner.png)](https://github.com/Warframe-Community-Developers "Supported by Warframe Community Developers")

### Parse the Warframe worldstate into useable javascript objects.


## GitHub
[![GitHub issues](https://img.shields.io/github/issues/Warframe-Community-Developers/warframe-worldstate-parser.svg)](https://github.com/aliasfalse/warframe-worldstate-parser/issues)
[![GitHub forks](https://img.shields.io/github/forks/Warframe-Community-Developers/warframe-worldstate-parser.svg)](https://github.com/aliasfalse/warframe-worldstate-parser/network)
[![GitHub stars](https://img.shields.io/github/stars/Warframe-Community-Developers/warframe-worldstate-parser.svg)](https://github.com/aliasfalse/warframe-worldstate-parser/stargazers)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/Warframe-Community-Developers/warframe-worldstate-parser/master/LICENSE)
[![Stories in Ready](https://badge.waffle.io/Warframe-Community-Developers/warframe-worldstate-parser.png?label=ready&title=Ready)](http://waffle.io/Warframe-Community-Developers/warframe-worldstate-parser) 

## Contact

[![Contact me on Discord](https://img.shields.io/badge/discord-Tobiah%238452-7289DA.svg)](https://discord.gg/bZgq6Pt "Contact me on Discord: Tobiah#8452")


## Installation
`npm i -S warframe-worldstate-parser`

## Documentation
You can find the documentation [here](https://Warframe-Community-Developers.github.io/warframe-worldstate-parser/)

## Example usage

```javascript
const WorldState = require('warframe-worldstate-parser');

const ws = new WorldState(json-data);

console.log(ws.alerts[0].toString());
```


## NPM
[![NPM](https://nodei.co/npm/warframe-worldstate-parser.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/warframe-worldstate-parser/)
