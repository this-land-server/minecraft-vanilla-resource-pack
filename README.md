
# This Land: Minecraft Vanilla Resource Pack

This is the custom resource pack used on This Land's Vanilla server. It provides custom textures and models for use with the [Custom Roleplay Data](https://www.curseforge.com/minecraft/customization/custom-roleplay-data-datapack) data pack.

## Adding custom models/textures to an item in-game

  1. Ensure you have at least 1 level of XP. It costs XP to customise items.

  2. Hold the item that you want to customise in your hand. The item _must_ be the one that the custom model is assigned to in this resource pack. See [`pack/assets/minecraft/models/item`](./pack/assets/minecraft/models/item/).

  3. Open chat, type `/trigger CustomModelData set <ID>` and hit enter. Change `<ID>` to a number which corresponds to a `custom_model_data` property in the item of your choice.

  4. The item should now have a custom model and texture.

As an example, if you wanted to have a straw hat to wear: obtain a carved pumpkin, hold it in your hand, run `/trigger CustomModelData set 2`, and wear your new hat.

## Creating new custom models/textures

Custom item models should be bound to a cheap item which can't be placed in the world. Generally `minecraft:iron_nugget`.

Custom hats etc should be bound to `minecraft:carved_pumpkin`.

  * [This guide](https://guide.denizenscript.com/guides/non-denizen/resource-packs.html) explains how some of this works
  * [Blockbench](https://web.blockbench.net/) is a good tool for creating custom models

## Deployment

The resource pack itself gets deployed automatically, but the SHA1 of the created zip file needs to be manually set in the server interface. For now, ask @rowanmanning to update this.

You can find the new SHA1 in the latest commit to the [website repository](https://github.com/this-land-server/website).

## Testing

Before opening a PR and deploying you should test changes in a local Minecraft world game. Symlink the `pack` folder into your local Minecraft instance's `resourcepacks/this-land` folder.
