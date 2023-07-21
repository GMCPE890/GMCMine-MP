# Rank (v1.1.0)
![](./assets/img/Rank/pack_icon.png?raw=true)
Rank Plugins for GMCMine-MP
<p align="center">[ <a href="./Not Found">Download Here !</a> ]</p>

> @Copyright by : `@GMCPE890`

<br />

## Requires (Function)
| Name | Version | See here |
| :--: | :-----: | :------: |

<br />

## Requires (Module)
| Name | Version | See here |
| :--: | :-----: | :------: |
| UI | v1.1.0 | <a href="./Not Found">Here !</a> |

<br />

## Commands List
| Default command | Parameter | Description | Default Permission |
| :-------------: | :-------: | :---------: | :----------------: |
| g-setrank | `<player>` | Give or assign a rank to the player | `Owner/®Operator` |

<br />

## Configuration

> File : `Plugins/Rank/configs.js`

| Key | Description | Available Value | Default Value |
| :-: | :---: | :---: | :-------: |
| listRank | List of all existing ranks | object | `owner & member` |
| defaultRank | gives default rank to players who don't have it yet | string | `member` |
| TextFormatDisplay | Format the text chat that the player comes out | string | `§8[($rank)§8] §e($name) §7>> §r($msg)` |
| TextDisplayActivate | To activate the chat format feature | bool | `true` |
| NameTagFormatDisplay | To format the NameTag in the player | string | `§8[($rank)§8] §f($name)§r` |
| NameTagDisplayActivate | To enable the NameTag Format feature | bool | `true` |
| permisionCommand | so that ranks other than those in the permission command cannot access commands such as set rank or delete rank | object | `{ Object }` |

<br />

## Change-Log
