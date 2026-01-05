---
---

# ConfigFlags

The `ConfigFlags` enumeration defines a set of bitwise flags used to configure window behavior, rendering options, and runtime hints. These flags can be combined using bitwise OR (`|`) to enable multiple configuration options.

---

- **Namespace:** Raylib_CSharp.Windowing
- **Type:** `enum`  
- **Underlying Type:** `uint`

---

## Usage

```csharp
ConfigFlags flags = ConfigFlags.FullscreenMode | ConfigFlags.VSyncHint;
```

## Flags
<table>
  <thead>
    <tr>
      <th>Flag</th>
      <th>Value</th>
      <th>Description</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>FullscreenMode</code>
      </td>
      <td>2</td>
      <td>Runs the application in fullscreen mode.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>ResizableWindow</code>
      </td>
      <td>4</td>
      <td>Allows the application window to be resized by the user.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>UndecoratedWindow</code>
      </td>
      <td>8</td>
      <td>Disables standard window decorations such as the frame and title bar.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>TransparentWindow</code>
      </td>
      <td>16</td>
      <td>Enables a transparent framebuffer for the window.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>Msaa4XHint</code>
      </td>
      <td>32</td>
      <td>Hints the system to enable 4× MSAA for improved visual quality.</td>
      <td>Hint only</td>
    </tr>
    <tr>
      <td>
        <code>VSyncHint</code>
      </td>
      <td>64</td>
      <td>Hints the GPU to enable vertical synchronization.</td>
      <td>Hint only</td>
    </tr>
    <tr>
      <td>
        <code>HiddenWindow</code>
      </td>
      <td>128</td>
      <td>Creates the window in a hidden state.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>AlwaysRunWindow</code>
      </td>
      <td>256</td>
      <td>Allows the application to continue running while minimized.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>MinimizedWindow</code>
      </td>
      <td>512</td>
      <td>Creates the window in a minimized (iconified) state.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>MaximizedWindow</code>
      </td>
      <td>1024</td>
      <td>Creates the window maximized to fill the monitor.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>UnfocusedWindow</code>
      </td>
      <td>2048</td>
      <td>Creates the window without input focus.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>TopmostWindow</code>
      </td>
      <td>4096</td>
      <td>Keeps the window always on top of other windows.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>HighDpiWindow</code>
      </td>
      <td>8192</td>
      <td>Enables High-DPI support for high-resolution displays.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>MousePassthroughWindow</code>
      </td>
      <td>16384</td>
      <td>Allows mouse input to pass through the window.</td>
      <td>Requires <code>UndecoratedWindow</code></td>
    </tr>
    <tr>
      <td>
        <code>BorderlessWindowMode</code>
      </td>
      <td>32768</td>
      <td>Runs the application in borderless windowed mode.</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <code>InterlacedHint</code>
      </td>
      <td>65536</td>
      <td>Hints the system to enable interlaced video output.</td>
      <td>V3D systems</td>
    </tr>
  </tbody>
</table>
