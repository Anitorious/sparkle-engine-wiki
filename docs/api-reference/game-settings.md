---
title: GameSettings
sidebar_position: 1
---

# GameSettings

The `GameSettings` struct defines the initial configuration for a **Sparkle Engine** application. It encompasses window dimensions, performance targets, and file system paths.

---

- **Namespace:** Sparkle.CSharp
- **Type:** struct
- **Underlying Type:** `struct`

---

## Usage

```csharp
GameSettings settings = new GameSettings()
{
    Title = "My Game",
};
```

## Properties

| Property          | Type          | Description                                                | Default Value                                      |
|-------------------|---------------|------------------------------------------------------------|----------------------------------------------------|
| **Title**         | `string`      | The title displayed on the application window.             | Dynamically fetched from `Assembly.GetEntryAssembly()`. Defaults to **"Sparkle"** if the assembly name is unavailable.                              |
| **Width**         | `int`         | The initial width of the game window in pixels.            | 1280                                               |
| **Height**        | `int`         | The initial height of the game window in pixels.           | 720                                                |
| **IconPath**      | `string`      | The file path to the application icon.                     | ""                                                 |
| **LogDirectory**  | `string`      | The directory where engine or application logs are stored. | "logs"                                             |
| **TargetFps**     | `int`         | The maximum frames per second. Set to 0 for uncapped.      | 0                                                  |
| **FixedTimeStep** | `int`         | The frequency of fixed update calls (e.g., physics).       | 60                                                 |
| **WindowFlags**   | [`ConfigFlags`](/docs/api-reference/config-flags) | Flags defining window behavior (e.g., VSync, Resizable).   | ConfigFlags.VSyncHint | ConfigFlags.ResizableWindow |
