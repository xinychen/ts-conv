# ts-conv
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
![Python 3.7](https://img.shields.io/badge/Python-3.7-blue.svg)
[![repo size](https://img.shields.io/github/repo-size/xinychen/ts-conv.svg)](https://github.com/xinychen/ts-conv/archive/master.zip)
[![GitHub stars](https://img.shields.io/github/stars/xinychen/ts-conv.svg?logo=github&label=Stars&logoColor=white)](https://github.com/xinychen/ts-conv)

<h6 align="center">Made by Xinyu Chen • :globe_with_meridians: <a href="https://xinychen.github.io">https://xinychen.github.io</a></h6>

[**Time series convolution**](https://spatiotemporal-data.github.io/posts/ts_conv): A convolutional kernel approach for reinforcing the modeling of time series trends and interpreting temporal patterns, allowing one to leverage Fourier transforms and learn sparse representations. The interpretable machine learning models such as sparse regression unlock opportunities to better capture the long-term changes and temporal patterns of real-world time series.

```bibtex
@article{chen2025correlating,
  title={Correlating time series with interpretable convolutional kernels},
  author={Chen, Xinyu and Cai, HanQin and Liu, Fuqiang and Zhao, Jinhua},
  journal={IEEE Transactions on Knowledge and Data Engineering},
  volume={},
  number={},
  pages={},
  year={2025},
  publisher={IEEE}
}
```

<br>


> To draw the graphics, please check out the [latex-graphics.ipynb](https://github.com/xinychen/ts-conv/blob/main/latex-graphics.ipynb) (Jupyter Notebook) in this repository.

## Implementation

### Data

- [NYC ridesharing and taxi trip data](https://github.com/xinychen/ts-conv/tree/main/NYC-data) (Source: [TLC trip record data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page))
- [Chicago ridesharing and taxi trip data](https://github.com/xinychen/ts-conv/tree/main/Chicago-data) (Source: [TNP ridesharing trips](https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips-2018-2022-/m6dm-c72p) | [Chicago taxi trips](https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips-2018-2022-/m6dm-c72p))
- [Fluid flow data](https://github.com/xinychen/ts-conv/tree/main/Fluid-flow)
- [North America temperature data](https://github.com/xinychen/ts-conv/tree/main/NA-temperature) (Source: [Daymet](https://daac.ornl.gov/DAYMET))

### Algorithms

How to solve the optimization problem of interpretable convolutional kernel learning?
- Non-negative subspace pursuit, NNSP
- Mixed-integer programming, MIP
