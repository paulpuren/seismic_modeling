# SeismicNet

**Physics-informed neural networks for seismic wave modeling in semi-infinite domain**

Paper link: [[CPC](https://www.sciencedirect.com/science/article/pii/S0010465523003557)], [[arXiv](https://arxiv.org/pdf/2210.14044.pdf)]

Authors: [Pu Ren](https://paulpuren.github.io/), [Chengping Rao](https://scholar.google.com/citations?user=29DpfrEAAAAJ&hl=en), [Su Chen](https://www.researchgate.net/profile/Chen-Su-5), [Jian-Xun Wang](https://sites.nd.edu/jianxun-wang/), [Hao Sun](https://scholar.google.com/citations?user=PaxAtLkAAAAJ&hl=en), [Yang Liu](https://scholar.google.com/citations?user=34upg6YAAAAJ&hl=en) 

## Highlights

- Present a new PINN model for seismic wave modeling in semi-infinite domain without the need for labeled data.
- Introduce the absorbing boundary conditions into the network as a soft regularizer for handling truncated boundaries.
- Leverage a sequential training strategy via temporal domain decomposition to improve the scalability of the PINNs.
- Design a novel surrogate modeling strategy to account for parametric loading, which estimates the wave propagation in semi-infinite domain given the seismic loading at different locations.

## Requirements

Forthcoming...

## Datasets

Forthcoming...

## Code

Forthcoming...

## Citation

If you find our research helpful, please consider citing us with：

```
@article{ren2023seismicnet,
  title={SeismicNet: Physics-informed neural networks for seismic wave modeling in semi-infinite domain},
  author={Ren, Pu and Rao, Chengping and Chen, Su and Wang, Jian-Xun and Sun, Hao and Liu, Yang},
  journal={Computer Physics Communications},
  pages={109010},
  year={2023},
  publisher={Elsevier}
}
```
