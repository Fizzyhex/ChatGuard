# ChatGuard
An easily implemented, non-intrusive chat bot prevention system for Roblox games.

## Releases
[Get the latest version from here!](https://github.com/metaVirtual/ChatGuard/releases)

## Installation
Drag the module into ServerScriptService.

## Documentation
*these functions are completely optional and aren't required for the bot protection that ChatGuard provides.*

```lua
ChatGuard:TrustPlayer(player, trusted [default: true]) [yields]
```
- Allows the selected player to send messages.
- Useful if you want to require players to do certain actions before they can chat,
- such as click a button or walk somewhere.

```lua
ChatGuard:IsPlayerTrusted(player) [yields]
```
- Check if a player is trusted. You may need to set TRUST_PLAYERS_BY_DEFAULT to false, depending on your use case.
- Returns a boolean.
