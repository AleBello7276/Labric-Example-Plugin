# Labric-Example-Plugin


## Labric?
Idk just so i have a name for this.
Labric = Legacy + Fabric.
This is still Work In Progress for LCE so don't expect much yet.

This Sample it's just an Hello World using XNotify

## How it works
i recently discovered that xenia allows to load plugins for games.
basically using the Xbox 360 Sdk we can compile dlls for games, using xenia we can load those dlls in a game to make cool things.
so in short it's just modding using dll injection :}


## Veryyy useful links
[Xenia Plugins Docs][PLdocs]
here we can find some info about plugins in xenia but not much.

[ClementDreptin ModdingResources][ModRes]
this guide will be a pretty useful starting point for hooking function and make them do cool things :}

## How to Build
(this is taken from my Decomp Project since i reused the Makefile)

This is a oversimplified guide to build the project.
on windows it works 100% since that's what I'm using, on linux and MacOs I don't know, if someone can run the Compiler and Linker EXEs on maybe Wine I think it can still work but I don't know

- First make sure to have a copy of the Xbox 360 XDK downloaded on your machine (I won't provide any guide on how to install it! you'll have to figure it out yourself)
- at the moment we'll just need the folders: bin/ lib/ and include/ also the documentation can be useful, the rest will not be used
- You need to set an Enviroment Varialble called "XEDK" which will be the root folder of the xdk (basically the folder where bin/ lib/ and include/ are located)
- Then just run ``make`` to build the project
- I recommend including the headers found in include/xbox in the IDE you are using, so intellisense will work with those, it will help a lot




[PLdocs]: https://github.com/AdrianCassar/game-patches/blob/plugin_docs/.github/Plugin-Docs.md
[ModRes]: https://github.com/ClementDreptin/ModdingResources
