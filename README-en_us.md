# [The COFH Word Cookbook - A Huge List of Examples, Screenshots, and Notes on Messing with Worldgen](https://www.reddit.com/r/feedthebeast/comments/818y32/the_cofh_word_cookbook_a_huge_list_of_examples/)

**Authored By *Fivefingeredfluke***

---

COFH world is a pretty powerful tool for easily adding ores/decorations/trees/spikes to the world gen. And while the specific settings for each generation option can be found on [COFH's site](https://teamcofh.com/docs/world-generator-configuration/), I had always wished there were more full example of how the settings could be used. So I present you the big list of COFH world setting examples with screen shots and such. (These have all been generated with only vanilla and thermal mods. The frequency is turned up way too high on most of these so they were easy to spot during testing)

## Boulder Generation - Snowballs
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/snow_balls.json)
- ![Screenshot](https://i.imgur.com/bK6rnCv.png)
- Notes: Generates snowball decorations only on the surface in biomes that are classified as 'snowy' or 'frozen'.
## Boulder Generation - Deep Ores
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/deep_boulder.json)
- ![Screenshot](https://i.imgur.com/xWRvRjd.png)
- Notes: Creates boulders close to bedrock that are made of 80% netherrack and 20% netherquartz. Good example of how to use weighted blocks in generation.
## Lake Generation - Nether Pyro Lakes
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/nether_lake.json)
- ![Screenshot](https://i.imgur.com/DALkQQp.png)
- Notes: Lakes made of blazing pyrotheum that only generate in the nether and are outlined with a mix of magma and netherwart blocks. An example of dimension restriction.
## Lake Generation - Hidden Enderium Lakes
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/end_lake.json)
- ![Screenshot](https://i.imgur.com/v11DYLK.png)
- Notes: Turns out it's hard to take a picture of hidden features. This is an example of using the lake 'gap' block set to endstone to hide the actual lake. The glass in the screen shot would normally be endstone, be careful mining.
## Geode Generation - Floating Lava Orbs
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/lava_geode.json)
- ![Screenshot](https://i.imgur.com/Ipzmgiq.png)
- Notes: Geodes can have one outline block surround another set of interior blocks (nicely used in one pack to generate rare ores in a shell of obsidian). Here the exterior is glass and the interior is lava. An example that 'air' can be used as the material features will generate in, if you don't mind things floating.
## Stalagmite Generation - Sand Spikes
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/sand_spikes.json)
- ![Screenshot](https://i.imgur.com/xvHi4H5.png)
- Notes: This example actually taught me something. Much like you can have a weighted list of blocks to generate, you can also have a weighted list of generators to select from. In this screen shot you can see sandstone spikes are generation is selected about 60% of the time with red sand/magma spike being generated less often. This weighted generation could be used to do things like make 1 in 10 iron ore veins generate as dense iron ore.
## Stalagmite Generation - Oil Wells
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/oil_well.json)
- ![Screenshot](https://i.imgur.com/YsGcehi.png)
- Notes: Although I couldn't quite get the deep oil reservoirs to generated, these oil stalagmites make a pretty good recreation of the old buildcraft oil wells.
## Tree Generation - Solid Gold Trees
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/gold_trees.json)
- ![Screenshot](https://i.imgur.com/M9aRzQ0.png)
- Notes: Couldn't really come up with something creative to do with tree generation, so here's an example of trees made with gold blocks for leaves.
## Spike Generation - End Spikes
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/end_spikes.json)
- ![Screenshot](https://i.imgur.com/cXl2erv.png)
- Notes: Using the shape of ice spikes in vanilla, this creates spikes of obsidian in the end. I didn't intend for the spikes to generate down in the void, but it creates an interesting feature for players without flight to try and throw enderpearls at.
## Fractal Large Vein Generation - Fake End Caves
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/fake_cave.json)
- ![Screenshot](https://i.imgur.com/BIucaI2.png)
- Notes: WARNING: This will cause horrible cascading world gen and would have to be pregened to be usable. The screen shot is from spectator mode while in the end island, so what you see are the pockets of air or fake caves carved out by this generation. Just an interesting idea.
## Plate Generation - Perfect Ore Layers
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/world_layers.json)
- ![Screenshot 1](https://i.imgur.com/B1Femns.png)![Screenshot 2](https://i.imgur.com/22AmEok.png)
- Notes: A bit longer of a json than some of the other examples. This defines a very specific layer for each ore with andesite/granite buffer layers between the ores.
## Cave Distribution - No Strip Mining
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/cave_world.json)
- ![Screenshot 1](https://i.imgur.com/LOnlY63.png)![Screenshot 2](https://i.imgur.com/rUL4YWA.png)
- Notes: Someone in discord brought up the idea of a world where ores only generate in caves to discourage players from doing boring strip mines. The first screen shot shows the world in spectator mode, so you can see where the caves exist. The second screen shot shows a stripped version of the same cave, showing how the ores only stick to where caves generate.
## Stalactite Generation - Spooky Trees
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/spider_trees.json)
- ![Screenshot](https://i.imgur.com/5tXIR2s.png)
- Notes: Using really tiny stalactites, you can add small cobwebs to the underside of some trees. An example of restriction by biome name, these only generate in roofed forests.
## Vein Generation - Weird Petrotheum Lake
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/petro_vein.json)
- ![Screenshot 1](https://i.imgur.com/qRDd9NJ.png)![Screenshot 2](https://i.imgur.com/PrPea7G.png)
- Notes: Using the a vein generation setting with distribution only on the surface, you can make lakes that look a little less normal. These petrotheum lakes often only have small spots sticking above the surface with the body of the fluid below. Only generates in the desert. First screen shot shows how they normally appear, the second screen shot is the same generation method using melon blocks so you can see how much of the fluid generates just below the surface.
## Underfluid Distribution - Cryotheum Ores
- [JSON link 1](https://github.com/superfluke/cofh-world-examples/blob/master/world/00_cryo_lake.json) & [JSON link 2](https://github.com/superfluke/cofh-world-examples/blob/master/world/frosty_ores.json)
- ![Screenshot](https://i.imgur.com/UHqJxRX.png)
- Notes: This one took quite a few tests to get rights and I quite like the end result. Unlike the other examples, this one takes 2 separate jsons. The first creates cryo lakes in snowy/frozen biomes, then the second generates very small clusters of either diamond or lapis under fluid cryotheum. An interesting example of how one generation (the ores) can depend upon the generation of another feature (the cryo lakes).
These last few are the least exciting examples, but are included for completeness.
## Uniform vs. Gaussian Distribution
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/uniform_gaussian.json)
- ![Screenshot](https://imgur.com/sOJxdRf.png)![Ore Distribution Graph](https://i.imgur.com/67Nc4j6.png)
- Notes: While the overall cluster shape is the same, you can see in the distribution graph that uniform has a more even distribution (shockingly) while gaussian is very high at a specific y-level and slowly decrease over a distance. Copper has the normal distribution, while tin is the gaussian distribution
## Cluster vs. Sparse Cluster Distribution
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/sparse_cluster.json)
- ![Screenshot](https://i.imgur.com/mrv9Iex.png)
- Notes: With the same cluster size and cluster count settings, the cluster generation seems to produce more overall with clusters between 1-4 ores large. Sparse Cluster generation produce a lot fewer over all clusters, with most being only 1 ore large. Copper is the normal cluster, while tin is the sparse cluster.
## Large Veins vs. Sparse Large Veins
- [JSON link](https://github.com/superfluke/cofh-world-examples/blob/master/world/large_vein_test.json)
- ![Screenshot](https://i.imgur.com/oPp2kw3.png)
- Notes: To be honest, I can't really see a difference with the large vein sparse setting turned on. But here's the screenshot anyway so you all can be the judge, copper is the large-veins normal while tin is the large-veins sparse

---

If you made it this far, thanks for checking out this excessively long post :D I hope I inspired some modpack makers to add some cool things to their world or just gave others a working example for messing with world gen. Feel free to steal, remix, or add onto any of these examples. If you'd like to check out my pack which has peat lined lakes and underground boulders made of skystone and custom osmatic steel ore, here's a link to [Undiscovered](https://minecraft.curseforge.com/projects/undiscovered).
