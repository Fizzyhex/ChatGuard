# ChatGuard
An easily implemented, non-intrusive chat bot prevention system for Roblox games.

## Releases
[Get the latest version from here!](https://github.com/metaVirtual/ChatGuard/releases)

## Installation
Drag the module into ServerScriptService.

## Documentation
*These functions are completely optional and aren't required for the bot protection that ChatGuard provides.*

```lua
ChatGuard:TrustPlayer(player, trusted [default: true]) [yields]
```

- Allows the selected player to send messages.
- This is useful for implementing your own tasks that users need to complete in order to chat, such as clicking a button or walking somewhere.
**- You need to change TRUST_PLAYERS_BY_DEFAULT to false if you would like to implement your own checks as well! **

```lua
ChatGuard:IsPlayerTrusted(player) [yields]
Returns: true/false
```

- Check if a player is trusted.
