# Quack Modloader 🦆

## Features:

Ever hankered for a goose modloader in Lua? Well, here you go!

Get it: [Quack Lua](https://github.com/DesktopGooseUnofficial/ResourceHub/releases/download/quack-0.1/GOOSE_LUA_V01.zip)

**⚠ SUPER EARLY ALPHA**. CONTACT MOD AUTHOR IF ISSUES OR SUGGESTIONS/QUESTIONS APPEAR.

Goose Version: **v0.21**

Mod Version: **v0.1**

Author: **easy bake oven#6781**

---
Functions:

| Function          | Arguments                                                                       | Purpose                                                                   |
|-------------------|---------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| GetGooseProp      | (string property) returns *something*                                           | Gets the property inside the goose (position, direction, etc)             |
| SetGooseProp      | (string property, object value)                                                 | Sets the property inside the goose (position, direction, etc)             |
| DrawRect          | (table position, table size, string[color] color) returns bool                  | Puts a rectangle on screen with the specified position, size, and color.  |
| DrawText          | (table position, string content, string[color] color, number size) returns bool | Puts text on screen with the specified position, content, color, and size |
| MeasureText       | Same as above, returns table                                                    | Gets the measurements of the specified text.                              |
| GetMousePos       | None, returns table                                                             | Gets the mouse's position on the screen.                                  |
| GetMouseHeld      | None, returns bool                                                              | True if left mouse button is held, otherwise false.                       |
| MessageBox        | (string message)                                                                | Shows a textbox on the user's screen. Limit of 3 at once.                 |
| MessageBoxAsk     | (string message) returns bool                                                   | Shows a textbox on the user's screen with yes and no. True if yes.        |
| MessageBoxIcon    | (string message, string icon)                                                   | Shows a textbox on the user's screen with specified icon. Icons at bottom.|
| MessageBoxIconAsk | (string message, string icon) returns bool                                      | Same as MessageBoxAsk, but with an icon.                                  |
| MessageBoxInput   | (string message, string default) returns string                                 | Asks user for text input with message.                                    |

---

## Color Table

![Has a list of colors that can be used for the goose's color palette here https://docs.microsoft.com/en-us/dotnet/api/system.windows.media.colors?view=netframework-4.8](https://docs.microsoft.com/en-us/dotnet/media/art-color-table.png?view=netframework-4.8 "A  list of color that can be used")

If you are unable to see the image you can click [here](https://docs.microsoft.com/en-us/dotnet/api/system.windows.media.colors?view=netframework-4.8)

## Icons

Error:
![Error icon](https://docs.microsoft.com/en-us/dotnet/media/messagebox-error.png?view=netframework-4.8 "Error icon")

Warning:
![Warning icon](https://docs.microsoft.com/en-us/dotnet/media/messagebox-warning.png?view=netframework-4.8 "Warning icon")

Information:
![Information icon](https://docs.microsoft.com/en-us/dotnet/media/messagebox-information.png?view=netframework-4.8 "Information icon")
