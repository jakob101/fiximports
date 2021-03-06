## Remove headaches when refactoring your app!

When you have a bunch of relative paths to fix, just right click on the parent folder and fix all of them at once.
Alternatively, you can press open command palette `F1` and search for `Relative Path Refactor`.

![GIF](https://media.giphy.com/media/3oz8xyRQqsATPdD9bW/source.gif)

## How to use

First, you will need to install Visual Studio Code. In the command palette (`Ctrl-Shift-P` or `Cmd-Shift-P`) select `Install Extension` and choose `RelativePathRefactor`.
It will keep extensions for relative paths that have them and remove when they don't.

## Important

Make sure you have committed all your work so you can revert changes made by this plugin. Additionally, If your folder has many files, it might take a while to fix all of them. Be patient!

## Known issues

First, I expect some bugs. I will fix them asap. Please report!
If there's many files to fix, some may stay unsaved. At the end, please save them. I'm working on fixing this.
Currently only paths that start with `.` are supported. Working on that as well.
If there are multiple possible choices of files, the relative path will ignore that line.

## Options

No options available yet.

## Bugs

Report them [here](https://github.com/jakob101/RelativePathRefactor/issues).

## Licence

[MIT](https://github.com/Microsoft/vscode-go/blob/master/LICENSE)