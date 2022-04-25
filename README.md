StoneScripts for my StoneStoryRPG
================================================

My StoneScript code used in the **amazing** ASCII-art game [Stone Story
RPG](https://store.steampowered.com/app/603390/Stone_Story_RPG/)
to automate it.

> Check when the scripts were relased vs. what the game version was
> [at the time](https://stonestoryrpg.com/releasenotes/), as the
> code may not be compatible with your (later) version of the game.


What is this?
----------------------------------------

The game Stone Story RPG allows you to write a script to automate the player's
behaviour in the levels, so you don't have to keep looking and change weapons
at the proper times. It's great to let the game loops the levels and farm
automatically.

This option is available after beating the final boss for the
first time. Once you do, you'll get the Mind stone, which can
be used to write the script (or to paste an existing one into it).

- [Official intro to scripting](https://stonestoryrpg.com/stonescript/)
- [Full manual of the Stone Script language](https://stonestoryrpg.com/stonescript/manual.html)


Usage
----------------------------------------

1. Clone this repository into a subfolder of the StoneScript directory (\*)
   called `my`. On Windows the directory is:
   
   ```text
   %AppData%\LocalLow\Martian Rex, Inc_\Stone Story\<Steam ID>\Stonescript
   ```
   
   The cloning command should thus look like
   
   ```bash
   cd %AppData%\LocalLow\Martian Rex, Inc_\Stone Story\<Steam ID>\Stonescript
   git clone https://github.com/TheMatjaz/StoneScript.git my
   ```

2. Copy-paste the content of the
  [mindstone.txt](https://raw.githubusercontent.com/TheMatjaz/StoneScript/master/mindstone.txt)
  file into the in-game Mindstone UI. This will load all other sub-scripts,
  one per level.

3. Modify the scripts as you please for your own playing.
   Hold TAB for debug information while playing a level.
