# Do We Take Shelter?: *Evaluating "high stakes" information*

Link to game: https://chantalmb.github.io/do_we_take_shelter-pt2/

## Folder structure
- `index.html`: Published game file
- `source`
  - `main.tw`: Passages that make up the central/narrative parts of the game
  - `families`: Passages associated with each family
  - `main.css`: Game styling
  - `config.js`: Updating game default configuration

## Workflow
1) Installed [Tweego](https://www.motoslave.net/tweego/) using [this script](https://gist.github.com/jsoma/5ef3045b2004a610455f371479a6f0cf).
2) Downloaded the [latest stable version of SugarCube](https://www.motoslave.net/sugarcube/2/).
3) Located the `tweego` directory and under `storyformats` replaced the existing outdated version of SugarCube with the one I downloaded in step 2.
4) Downloaded [the minimal VSCode/Tweego template from this tutorial](https://joshuagrams.github.io/tiny-qbn/doc/tweego.html) and opened it in VSCode.
5) Installed the `Twee 3 Language Tools` extension in VSCode.
6) Opened a terminal in VSCode and ran `tweego -o index.html main.tw` to get an IFID, which is added under `StoryData` in `main.tw`.
7) To test the story as it's developed + build the published file, run `tweego -o index.html source`!    