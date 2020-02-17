## Installation guide

First, make sure that you are running Desktop Goose v0.3.

There should be a "Mods" folder in the "Assets" folder. If not, you're running v0.2.
Go to the [Desktop Goose page on itch.io](https://samperson.itch.io/desktop-goose) to download v0.3.
The macOS version does not support mods yet.

**Need help? Something not working right?** Feel free to ask for support in the [#goose-mods channel on the discord server](https://discord.gg/yjGFsUD). 

1. Go to the `Mods` folder in the `Assets` folder. {% if include.iszip %}
2. Open the `{{ include.modname }}.zip` file.
3. Copy the folder from the `{{ include.modname }}.zip` file to the `Mods` directory. {% else %}
2. Create a folder with the name `{{ include.modname }}`.
3. Place the `{{ include.modname }}.dll` file inside the `{{ include.modname }}` folder. {% endif %}
4. Go back to the Desktop Goose folder.
5. If you haven't already, open `config.ini` and change `EnableMods=False` to `EnableMods=True`
6. If you haven't already, save the `config.ini` file.
7. Done!
