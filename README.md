# gol

(means game of life)

Simple Game of life in C using Raylib.

Simply run:

```
./gol
```

There are some commands:

| Input   | Function                                     |
| ------- | -------------------------------------------- |
| 1       | Enter 'Run' Mode (default)                   |
| 2       | Enter 'Step' Mode                            |
| space   | Start / stop the simulation                  |
| l       | Load the 'save.gol' file into the simulation |
| s       | Save the current state into 'save.gol'       |
| c       | Clear the simulation state                   |

The 'save.gol' file is plain text 1's and 0's to allow for direct editing with your text editor if it is preferred over clicking.

## Screenshots

![Three gliders](/screenshots/screenshot.png)

Uses [Raylib](https://github.com/raysan5/raylib) for window creation, drawing, and input handling.
