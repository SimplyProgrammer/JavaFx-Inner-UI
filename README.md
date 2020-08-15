## About
InnerUI adds some king of window system you can have inside of your JavaFx application.
Basically it adds window into window or in other words layout nodes with user interface!
I never planned to release this thing. This was my attempt to create whole operation system but suddenly I realized that it will not be that easy. I mean, it was utopia to think that one person will make entire operation system. But I thought it would be nice if I publish that what I manage to create before I stop with operation system development. So that's Inner UI.
Feel free to report any problems, issues or what I should add or change.

## Info
* If you want to add or see issues just click on [Issues section](https://github.com/PetoPetko/InnerUI/issues) in up.
* If you want to comment use [Issues section](https://github.com/PetoPetko/InnerUI/issues) too.
* If you want to see or learn some things about library click, download documentation or open-source Examples Pack.
* If you want to download library, dont use commits section, use [Releases section](https://github.com/PetoPetko/InnerUI/releases) or click that big green button "Clone or download" to download the latest version.
* And if you want to see changelog open [changelog file](Changelog.md) or use [Releases section](https://github.com/PetoPetko/InnerUI/releases) too.

Ps. Please visit this page sometimes again, because the new version may be release.

## Information about update 1.3.0
In updat 1.3.0 there will be rework of entire window system. 
The main thing is WindowBase will extends Node so now you will be able to add window directly in to your layout node.
This will bring alot of changes like:
* Class UpdateHandler will be removed followed by every method that is working with UpdateHandlers and will be replaced with JavaFx properties!
* Based on previous point WSS will be changed or even completely replaced by CSS.
* MoveableWindow will be merged with EmptyWindow.
* LogicalHandler and PrimitiveHandler will be also removed and replaced by JavaFx event systen.
* Also all interfaces (Moveable, Resizable...) will be removed because I find them useless.
* Class Manager might be changed or completely removed but this is unlikely.
* Some method become "Deprecated" meaning you should not use it but you will have alot of time to find other solution.
