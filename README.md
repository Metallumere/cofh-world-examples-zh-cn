# [CoFH World 经典实用案例——内含大量实例、截图及纠结于世界生成时所注意的内容](https://www.reddit.com/r/feedthebeast/comments/818y32/the_cofh_word_cookbook_a_huge_list_of_examples/)

**作者：*Fivefingeredfluke***

**翻译：*SihenZhang***

---

CoFH World 是一个非常强大的工具，它可以轻松地将矿石、装饰物、树木或尖刺添加到世界生成当中。虽然每个生成选项的特定设置都可以在 [CoFH 的网站](https://teamcofh.com/docs/world-generator-configuration/) 上找到，但我一直希望能够有更为完整的实例来说明如何使用这些设置。所以我以截图等方式向你展示了大量的 CoFH World 的设置实例。（这些实例都是只由原版和 Thermal Mods 生成的。大多数实例的“frequency（频率）”都被调的很高，所以在测试过程中很容易被发现。）

## 巨石型生成——雪球
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/snow_balls.json)
- ![Screenshot](https://i.imgur.com/bK6rnCv.png)
- 注意：这个例子只会在被归类为“snowy”或“frozen”的生物群系中才会生成这种雪球装饰物。
## 巨石型生成——深层矿物
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/deep_boulder.json)
- ![Screenshot](https://i.imgur.com/xWRvRjd.png)
- 注意：这个例子会在基岩附近生成由 80% 地狱岩和 20% 下界石英构成的巨石。这是一个如何在生成中使用方块权重的好例子。
## 湖泊型生成——下界烈焰之炽焱湖
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/nether_lake.json)
- ![Screenshot](https://i.imgur.com/DALkQQp.png)
- 注意：这个例子只会在下界生成由炽热的烈焰之炽焱构成的湖泊，并且会有着混有岩浆块和地狱疣块的边缘。这也是一个限制维度的例子。
## 湖泊型生成——隐藏的谐振熔融末影珍珠湖
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/end_lake.json)
- ![Screenshot](https://i.imgur.com/v11DYLK.png)
- 注意：从结果上来说，很难通过截图来表现湖泊被隐藏的特点。这个例子将湖泊的“gap-block（间隙方块）”设置为末地石来达到隐藏真实湖泊的效果。截图中的玻璃应为末地石，请小心挖掘。
## 晶球型生成——浮空熔岩球
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/lava_geode.json)
- ![Screenshot](https://i.imgur.com/Ipzmgiq.png)
- 注意：晶球型生成可以以一种外部的方块来包围另一种内部的方块（在整合包里你可以巧妙地将一些稀有的矿物生成在黑曜石外壳之中）。这个例子中的外部是玻璃，内部是熔岩。如果你不介意有东西漂浮在空中的话，那么这是一个很好的以空气作为“material（材料）”特征并生成在空中的例子。
## 石笋型生成——沙锥
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/sand_spikes.json)
- ![Screenshot](https://i.imgur.com/xvHi4H5.png)
- 注意：这个例子其实说明了一些东西。就像你可以对要生成的方块列出一个权重列表，你也可以为你所选的生成器类型列出一个权重列表。在这张截图中你可以看到红砂岩与岩浆块形成的锥刺相对更少一些，大约是砂岩锥刺生成倍率的 60% 。这种加权生成可以被用来做一些东西，诸如 10 个铁矿石矿脉中有 1 个矿脉是由密集铁矿石构成。
## 石笋型生成——油井
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/oil_well.json)
- ![Screenshot](https://i.imgur.com/YsGcehi.png)
- 注意：尽管我不能完全生成出地下的深层油藏，但是这些石笋型的石油依旧很好的重现了老版 Buildcraft 的油井。
## 树型生成——金块树
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/gold_trees.json)
- ![Screenshot](https://i.imgur.com/M9aRzQ0.png)
- 注意：我实在想不出有关树型生成的有趣点子，所以这里展示了一个以金块为树叶构成的树的例子。
## 尖刺型生成——末地尖刺
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/end_spikes.json)
- ![Screenshot](https://i.imgur.com/cXl2erv.png)
- 注意：这个例子在末地使用原版冰刺的形状生成出黑曜石尖刺。我本不打算在虚空中生成尖刺，但这却为没有飞行能力的玩家提供了一个有趣的玩法——往尖刺上扔末影珍珠。
## 分形大型矿脉型生成——仿造的末地洞穴
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/fake_cave.json)
- ![Screenshot](https://i.imgur.com/BIucaI2.png)
- 注意：警告：这个例子会导致规模恐怖的连续世界生成，且必须要进行预生成才可使用。截图以旁观模式在末地岛内部截取，所以你实际上看到的应该是由这个例子生成的空洞或者说仿造的洞穴。只是个有趣的想法而已。
## 平面型生成——完美矿石层
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/world_layers.json)
- ![Screenshot 1](https://i.imgur.com/B1Femns.png)![Screenshot 2](https://i.imgur.com/22AmEok.png)
- 注意：这个例子的 JSON 文件要比其它例子的稍长一些。这个例子为每种矿石都预设了特定的层且矿物之间有安山岩或花岗岩构成的缓冲层。
## 洞穴型生成——禁止鱼骨形挖矿
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/cave_world.json)
- ![Screenshot 1](https://i.imgur.com/LOnlY63.png)![Screenshot 2](https://i.imgur.com/rUL4YWA.png)
- 注意：有人在 Discord 上提出了一个点子——矿物只会生成在洞穴中，避免玩家无聊地鱼骨形挖矿。第一张截图以旁观模式展示了这个例子的世界生成，你可以看到洞穴都在哪里。第二张截图则是将石头去掉后对同一个洞穴进行展示，可以看到矿物只会生成在洞穴所在的地方。
## 石笋型生成——阴森的树
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/spider_trees.json)
- ![Screenshot](https://i.imgur.com/5tXIR2s.png)
- 注意：利用非常小的石笋，你可以在树的下方添加一些小型的蜘蛛网。这也是一个限制生物群系名称的例子，它只会生成在“roofed_forest（黑森林）”群系。
## 矿脉型生成——诡异的板块之层岩湖
- [JSON 链接](https://github.com/superfluke/cofh-world-examples/blob/master/world/petro_vein.json)
- ![Screenshot 1](https://i.imgur.com/qRDd9NJ.png)![Screenshot 2](https://i.imgur.com/PrPea7G.png)
- 注意：利用矿脉型生成并让其只在地表生成，可以生成出看起来不太寻常的湖泊。这些板块之层岩湖泊只会在地表露出一小点而在地下则生成了一大片。它只会在沙漠生成。第一张截图展示了它通常看起来是什么样子，而第二张截图则用西瓜块进行相同的生成，因此你可以看到在地表下方生成了多少液体。
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
