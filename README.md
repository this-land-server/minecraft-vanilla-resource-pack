
# This Land: Minecraft Vanilla Resource Pack

This is the custom resource pack used on This Land's Vanilla server. It provides custom textures and models for use with the [Custom Roleplay Data](https://www.curseforge.com/minecraft/customization/custom-roleplay-data-datapack) data pack.

Custom item models should be bound to a cheap item which can't be placed in the world. Generally `minecraft:iron_nugget`.

Custom hats etc should be bound to `minecraft:carved_pumpkin`.

  * [This guide](https://guide.denizenscript.com/guides/non-denizen/resource-packs.html) explains how some of this works
  * [Blockbench](https://web.blockbench.net/) is a good tool for creating custom models

## Deployment

The resource pack itself gets deployed automatically, but the SHA1 of the created zip file needs to be manually set in the server interface. For now, ask @rowanmanning to update this.

You can find the new SHA1 in the latest commit to the [public website repository](https://github.com/this-land-server/public).

## Testing

Before opening a PR and deploying you should test changes in a local Minecraft game. Symlink the `pack` folder into your local Minecraft instance's `resourcepacks/this-land` folder.
