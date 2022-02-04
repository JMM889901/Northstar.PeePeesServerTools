# Northstar.PeePeesServerTools

A collection of basic server tools

Adds autokick and automatically changes map on startup if the map is currently lobby

DO NOT USE WITH CLIENT, ONLY FOR DEDICATED SERVERS

This mod only works on servers as the lobby skip can and will work on the multiplayer screen

## Var overrides

 * SkipLobby
   - 0 or 1
 * AutoKick
   - If above zero, kicks a player after given number of minutes
 * ReplacementMap
   - Full name of a map, such as `mp_forwardbase_kodai`
 * ReplacementMode
   - Full name of a mode, such as `gg`

## ConVars

 * KickImmune
   - see `mod.json`
