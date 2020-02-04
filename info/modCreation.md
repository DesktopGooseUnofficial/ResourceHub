# Info for mod creators

The following assumes you are using *dnSpy*.

## Use a different version for the config

Go to `GooseConfig.ConfigSettings.ReadFileIntoConfig`, edit the method with CTRL+SHIFT+E and change `if (num != 0)` to `if (num != YOUR_CONFIG_VERSION)`

## Adding a config setting

Go to `GooseConfig.ConfigSettings.ConfigSettings()`, edit the method and add variables such as:
```csharp
public bool CanAttackAtRandom = true;
```

## Fix code decompiled by dnSpy

This only applies to the `TheGoose.cs` file.

- Line 531, 565, 567, and 532: Comment out

## Notepad phrases

Notepad phrases can be edited in `TheGoose.SimpleTextForm.possiblePhrases`
You can pull them from a file with:
```csharp
using System.IO;
File.ReadAllLines(Program.GetPathToFileInAssembly("phrases.txt"))
```

