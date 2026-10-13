# ymgu2000

## MatterFlow

[MatterFlow](https://github.com/ymgu2000/MatterFlow) is my research codebase for site-aware generation of A-site and B-site doped ABX3 perovskites. It adapts a MatterGen/GemNetT backbone to continuous fractional site occupancies and spherical flow matching. The current model predicts site occupancies using a supplied template structure; atomic coordinates and lattice vectors are inputs to this generation path.

The private repository contains the model source, training and generation code, and a [guide to the current C1 configuration](https://github.com/ymgu2000/MatterFlow/blob/main/core_matterflow/CURRENT_MODEL.md). Trained checkpoints and research datasets are not included. Generated candidates require separate structural and property evaluation.

中文：MatterFlow 是用于 ABX3 钙钛矿 A/B 位掺杂研究的位点感知生成模型代码。当前版本在给定模板结构的条件下生成位点元素占据，不直接生成新的原子坐标或晶格；目前仓库为私有，包含源码和使用说明，不包含训练权重或数据集。
