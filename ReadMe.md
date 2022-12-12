## Player Functions Include

This Include adds wide range of SA-MP Functions which enables the Script Developers to have extra control over their players! This include is compatible with the latest version of San Andreas Multiplayer (0.3.7)

This include adds the following functions -

```
native GivePlayerScore(playerid, score); // Adds score to a particular player
native SetPlayerMoney(playerid, money); // Resets money of a particular player to a particular amount
native RemovePlayerWeapon(playerid, weaponid); // Disarms a player of a specific weapon
native SetPlayerFacingPoint(playerid, Float:x, Float:y); // Changes the direction in which the player is facing
native IsPlayerFacingPoint(playerid, Float:x, Float:y, Float:range = 10.0); // returns true if a player is facing a particular direction
native SetPlayerFacingPlayer(playerid, targetid); // Makes 2 player face each other
native IsPlayerFacingPlayer(playerid, targetid, Float:range =  10.0); // returns true if a player is facing another particular player in a desired range
native IsPlayerBehindPlayer(playerid, targetid, Float:range = 10.0); // returns true if a player is standing behind another particular player in a desired range
native GetPlayerWeaponAmmo(playerid, weaponid); // returns the ammo of a particular weapon of a player
native SetPlayerWeaponAmmo(playerid, weaponid, ammo); // changes the ammo of a weapon to a specific amount
native IsPlayerHavingWeapon(playerid, weaponid); // returns true if player is having the specified weapon
native SetPlayerWalkingStyle(playerid, style); // changes the player walking style
native GetPlayerWalkingStyle(playerid); // returns the players walking style 
native GetPlayerSkillLevel(playerid, skill); // returns the player's skill level
```

This include adds the following callbacks -

```
public OnPlayerWalk(playerid, style) // This callback is triggered when a player begins to walk
```
