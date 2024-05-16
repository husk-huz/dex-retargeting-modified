Dex Retargeting
---
<p align="center">
    <!-- code check badges -->
    <a href='https://github.com/dexsuite/dex-retargeting/blob/main/.github/workflows/test.yml'>
        <img src='https://github.com/dexsuite/dex-retargeting/actions/workflows/test.yml/badge.svg' alt='Test Status' />
    </a>
    <!-- issue badge -->
    <a href="https://github.com/dexsuite/dex-retargeting/issues">
    <img src="https://img.shields.io/github/issues/dexsuite/dex-retargeting.svg" alt="Issues">
    </a>
    <!-- release badge -->
    <a href="https://github.com/dexsuite/dex-retargeting/tags">
    <img src="https://img.shields.io/github/v/release/dexsuite/dex-retargeting.svg?include_prereleases&sort=semver" alt="Releases">
    </a>
    <!-- license badge -->
    <a href="https://github.com/dexsuite/dex-retargeting/blob/main/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/license-MIT-blue">
    </a>
</p>

## Installation

```shell
# Install from pypi
pip install dex_retargeting`` 

# Or install from Github
git clone https://github.com/dexsuite/dex-retargeting
cd dex-retargeting
pip install -e .
```

To run the example, you may need additional dependencies for rendering and hand pose detection.

```shell
pip install -e ".[example]"
```

## Examples

### Retargeting from human hand video

[Tutorial on retargeting from human hand video](example/vector_retargeting/README.md)

### Retarget from hand object pose dataset

[Tutorial on retargeting from hand-object pose dataset](example/position_retargeting/README.md)

## Citation

This repository is a part of the [AnyTeleop Project](https://yzqin.github.io/anyteleop/). If you use this work, kindly
reference it as:

```shell
@inproceedings{qin2023anyteleop,
  title     = {AnyTeleop: A General Vision-Based Dexterous Robot Arm-Hand Teleoperation System},
  author    = {Qin, Yuzhe and Yang, Wei and Huang, Binghao and Van Wyk, Karl and Su, Hao and Wang, Xiaolong and Chao, Yu-Wei and Fox, Dieter},
  booktitle = {Robotics: Science and Systems},
  year      = {2023}
}
```

## Acknowledgments

This repository builds on the foundational work from [pinocchio](https://github.com/stack-of-tasks/pinocchio). Examples
within utilize a renderer derived from [SAPIEN](https://github.com/haosulab/SAPIEN).
The [PositionOptimizer](https://github.com/dexsuite/dex-retargeting/blob/main/dex_retargeting/optimizer.py) leverages
methodologies from our earlier
project, [From One Hand to Multiple Hands](https://yzqin.github.io/dex-teleop-imitation/). Additionally,
the [DexPilotOptimizer](https://github.com/dexsuite/dex-retargeting/blob/main/dex_retargeting/optimizer.py) is crafted
using insights from [DexPilot](https://sites.google.com/view/dex-pilot).

## License and Disclaimer

Web-Based Visualizer for Simulation Environments is released under the [MIT License](LICENSE).
