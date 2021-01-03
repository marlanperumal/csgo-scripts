# CSGO Scripts

Scripts and Config for running a Counter-Strike: Global Offensive dedicated server

## References

- [Official Valve Wiki](https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive_Dedicated_Servers)

## Run RCon Commands

In the CS console run

```
rcon_password <password> #Authenticate
rcon <alias> # e.g. `rcon cp_arms_race` changes the game mode to arms race. See https://github.com/marlanperumal/csgo-scripts/blob/master/cp.cfg#L77-L116 for more aliases
rcon bot_kick # Kicks bots
rcon bot_add_t # Adds bot to terrorist team
```

