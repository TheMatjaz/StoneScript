StoneScript
===========

My StoneScript code used in the **amazing** ASCII-art game [Stone Story
RPG](https://store.steampowered.com/app/603390/Stone_Story_RPG/)
to automate it.

> **NOTE:** this was written for Stone Story RPG v1.8.6 in September 2019. I
> haven't played the game since. The script may be incompatible with newer
> versions of the game.


What is this?
----------------------------------------

The game Stone Story RPG allows you to write a script to automate the player's
behaviour in the levels, so you don't have to keep looking and change weapons
at the proper times. It's great to let the game loops the levels and farm
automatically.

If you are confused by this and wonder where the script could be used, beat
the boss Nagaraja first. Once you do, you'll get the Mind stone, which can
be used to write the script (or to paste an existing one into it).



Usage
----------------------------------------

Copy-paste the
[script.txt](https://raw.githubusercontent.com/TheMatjaz/StoneScript/master/script.txt)
file into the mind stone. The script contains multiple conditionals to work in
every level. In case the script does not behave properly, verify that you
have a matching version of the game with the version indicated in the script.

In case you want to do any modifications, the documentation for the
scripting language _StoneScript_ is available on the [game
website](http://stonestoryrpg.com/stonescript/help.txt)

You are free to use the script as you wish as long as you include my name,
as indicated in the license.



Additional information about the game
----------------------------------------

### Elements and runes

- Vigor ❤ is strong against Aether ＊
- Aether ＊is strong against Fire φ
- Fire φ is strong against Ice ❄
- Ice ❄ is strong against Poison ∞
- Poison ∞ is strong against Vigor ❤

More information available
[here](https://github.com/Tomotopieces/runestone-in-ssrpg/blob/master/README_EnglishVersion.md)


### Potions

- Stone: `o`
- Wood: `` _/` ``
- Tar: `≈`
- Bronze: `:.`


1.  Tar (20): healing potion, restore all HP
2.  Stone (20): strength potion, 2x damage dealt + stun for 10 seconds
3.  Wood (20): experience potion, +1 XP and +1 Ki per killed enemy for 30
    seconds
4.  Bronze (20): lightning potion, deal 100 damage to all enemies on the screen
5.  Stone (10) + Wood (10): invisibility potion, 100% evasion for 15 seconds
6.  Stone(10) + Bronze (10): lucky potion, 100% critical attack chance for 7
    seconds or double damage if not critical attacks are possible
7.  Stone (10) + Tar (10): defensive potion, heal 50% HP, gain armor equal to 
    max HP (which starts to drop right away)
8.  Wood (10) + Bronze (10): berserk potion, +15 attack speed (2-5x more) for
    10 seconds
9.  Wood (10) + Tar (10): cleansing potion, restore 50% of HP, remove all
    debuffs
10. Bronze (10) + Tar (10): +20% lifesteal for 20 seconds

