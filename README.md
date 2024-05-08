# Godot 4.2 VSCode C# Project + Debug

A basic project boilerplate for Godot Engine C# projects with preconfigured debugging support for Visual Studio Code.

<br />
<img src="https://github.com/guasam/godot-vscode-project/assets/72690494/97b97375-2004-4e89-bd60-0b00ec57573f" />
<br />

## Prerequisites

- Godot Engine (C# Support aka .NET)
- Visual Studio Code
- Extension [godot-csharp-vscode](https://marketplace.visualstudio.com/items?itemName=neikeq.godot-csharp-vscode)

<br />

## Available Debug Configurations

| Type                     | Description                                                |
|--------------------------|------------------------------------------------------------|
| Debug Game               | Starts the game with debugging enabled to identify and address available breakpoints in scripts. |
| Launch Editor            | Starts the Godot Editor with the default scene.            |
| Launch a Scene           | Prompts to select a scene to start the game for debugging. |
| Attach to Process        | Attaches to an existing running game process to debug assigned breakpoints. |

<br>

Make sure to update `.vscode/launch.json` for correct path of godot executable for all launch configurations:

```json
"program": "<path_of_godot_exe>",
```
