# Snake (Blazor WebAssembly, .NET 9)

Classic Snake game built with Blazor.

## How to play
- Arrow keys or W/A/S/D move the snake. Space = start / pause. Enter = restart.
- On-screen buttons are available for mouse / touch.
- Eat the red food to grow (+10 points). Hitting a wall or yourself ends the game.
- Every 5 foods the level goes up and the snake moves faster.

## Features
- Game loop with `Task.Delay` + `CancellationToken` (pause / resume / restart).
- Level system that increases the speed.
- **High score saved in the browser** (`localStorage` through JS interop), so it survives page reloads.
- Keyboard accessible, `aria-live` status messages.

## Run
```
cd SnakeGame
dotnet run
```
Open http://localhost:5117
