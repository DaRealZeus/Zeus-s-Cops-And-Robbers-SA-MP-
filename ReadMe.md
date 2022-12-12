## Player Functions Include

This library is developed for San Andreas Multiplayer, and this include adds a wide range of SA-MP Functions which enable script developers to gain extra control over their players. This include is compatible with the latest version of San Andreas Multiplayer (0.3.7)

This include adds the following functions -

```
native GetDayName(day); // Returns the day of the week in-game
native CreateBlood(playerid); // Creates a custom blood particle around a player, can be used with "OnPlayerTakeDamage" for visual purposes
native GivePlayerScore(playerid, score); // Adds score to a particular player
native SetPlayerMoney(playerid, money); // Resets money of a particular player to a particular amount
native RemovePlayerWeapon(playerid, weaponid); // Disarms a player of a specific weapon
native SetPlayerFacingPoint(playerid, Float:x, Float:y); // Changes the direction in which the player is facing
native IsPlayerFacingPoint(playerid, Float:x, Float:y, Float:range = 10.0); // Returns true if a player is facing a particular direction
native SetPlayerFacingPlayer(playerid, targetid); // Makes 2 player face each other
native IsPlayerFacingPlayer(playerid, targetid, Float:range =  10.0); // Returns true if a player is facing another particular player in a desired range
native IsPlayerBehindPlayer(playerid, targetid, Float:range = 10.0); // Returns true if a player is standing behind another particular player in a desired range
native GetPlayerWeaponAmmo(playerid, weaponid); // Returns the ammo of a particular weapon of a player
native SetPlayerWeaponAmmo(playerid, weaponid, ammo); // Changes the ammo of a weapon to a specific amount
native IsPlayerHavingWeapon(playerid, weaponid); // Returns true if player is having the specified weapon
native SetPlayerWalkingStyle(playerid, style); // Changes the player walking style
native GetPlayerWalkingStyle(playerid); // Returns the players walking style 
native GetPlayerSkillLevel(playerid, skill); // Returns the player's skill level
```

This include adds the following callbacks -

```
public OnPlayerWalk(playerid, style) // This callback is triggered when a player begins to walk
```

Credits -

```
Niket Gandhir - Developing this Include
SA-MP Team (Past and Present) - For Developing San Andreas Multiplayer
```

This include was last updated on - 12 December 2022
