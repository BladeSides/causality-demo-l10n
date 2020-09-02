# Contributing to localizing Causality game's demo

Thanks for joining to here!

The following is a list of contributing guidelines for Causality game's demo localization.

- 1. The directory `ko` is source dialogue content of the game.
- 2. Copy `ko` and rename to you want to translate language's [ISO-639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) code.  
     i.e. japanese is `ja`, english is `en`...
- 3. Translate them!
  - `Plugins.json`
    - Don't need to translate `snackbar-templates`'s `name` key.
  - Common cases
    - You shouldn't add additional array strings.
    - Starting with `\\` is dialogue control command.  
      More info : https://forums.rpgmakerweb.com/index.php?threads/about-messages-commands.84996

# How to test play

1. Download standalone game at here.  
[Download](https://creffect.com/project/causality-game/download/demo.zip)

2. Extract it and open `www/lang` directory and
   put your translated content into here.

3. Run `Game.exe`, and go to `환경 설정` -> `언어 | 한국어`
   and change it to your language.

4. Start to check your work!