# PokeStatsJsObj
The names, stats, types, and forms for all Pokemon as of 12/15/2015.
All the stat information is stored as an array of js objects in the variable "pkmn_stats".
The acceptable fields for each pokemon object are:
* id - string: pokemon's national dex #
* name - string: pokemon's name
* type - [string | object]: the pokemon's type OR types (if multiple, will be an array of type string)
* total - string: total of all pokemon's stats
* hp - string: pokemon's hit points
* atk - string: pokemon's physical attack
* def - string: pokemon's physical defense
* spatk - string: pokemon's special attack
* spdef - string: pokemon's special defense
* spd - string: pokemon's speed
