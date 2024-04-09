# Contributing Guide

Want to add some games to an existing video game mechanic list, or create a new list? There's a few ways.

This is the structure of the repo:

- All content lives under `/content/`.
- Create new lists and game files with no spaces, instead use `-`.
    - For games, at the end include the year they were released as well.
- Video game mechanics lists live under `/content/`.
- If you want to add a game so you can link it in the lists, create a new markdown file under `/content/games/` and name the file with the game name and year. 
- Copy the toml metadata from an existing markdown file, paste it into the new file, and edit it.
- To link to a game, use this syntax: `[Outer Wilds](@/games/outer-wilds-2019.md)`. An example can be found [here](content/time-loop.md).

## Fork and create a pull request

Fork the repo, make your changes, then create a pull request.

## Create an issue

You can also [create an issue](https://github.com/StringPotatoTheory/awesome-video-game-mechanics/issues) to either edit an existing list, or create a new one. If you would like to make changes to an existing list, please mention or link to the list.

## Edit the markdown files in github

Learn how to do this [here](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files#editing-files-in-another-users-repository).

## License

Content is licensed with [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
