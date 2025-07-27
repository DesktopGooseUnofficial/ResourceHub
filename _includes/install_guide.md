## Installation guide

First, make sure that you are running [Desktop Goose 0.3/0.31](https://samperson.itch.io/desktop-goose) on Windows. The macOS version does not support mods.

0. If you have the Goose running, close him first.
1. Go to the `Mods` folder in the `Assets` folder. {% if include.iszip %}
2. Open the `{{ include.modname }}.zip` file.
3. Copy the folder from the `{{ include.modname }}.zip` file to the `Mods` directory. {% else %}
2. Create a folder with the name `{{ include.modname }}`.
3. Place the `{{ include.modname }}.dll` file inside the `{{ include.modname }}` folder. {% endif %}
4. Go back to the Desktop Goose folder.
5. If you haven't already, open the `config.ini` file and change `EnableMods=False` to `EnableMods=True`, then save it.
7. Open the Goose again and enjoy!!

**Need help?** You can ask for support in the [#goose-modding channel on the Discord server](https://discord.gg/avXP7hsUt2). 
