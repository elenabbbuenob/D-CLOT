# [**D-CLOT: Double closed loop optimal transport for unsupervised action segmentation. **](https://arxiv.org/abs/2608.05877)

**Elena Bueno-Benito, Mariella Dimiccoli**
Institut de Robòtica i Informàtica Industrial, CSIC-UPC, Barcelona, Spain

> 🚧 **Code coming soon.** This repository will host the official PyTorch implementation of D-CLOT.

## Overview

D-CLOT extends [CLOT](https://arxiv.org/abs/2507.03539) for unsupervised temporal action segmentation. It regularises the refined frame embeddings with a graph that preserves the local neighbourhood structure of the encoder output. It also periodically re-estimates the latent action prototypes from these graph-constrained features. We propose two variants:

- **D-CLOT**: re-estimates the prototypes with k-means.
- **D-CLOT<sub>B</sub>**: re-estimates the prototypes as OT barycenters.

## Planned release

- [ ] Training and evaluation code
- [ ] Pretrained checkpoints for Breakfast, YouTube Instructions, 50Salads, Desktop Assembly and Assembly101
- [ ] V-JEPA 2 features for our Assembly101 unsupervised action segmentation benchmark

## Citation

```bibtex
@article{buenobenito2026dclot,
  title   = {D-CLOT: Double Closed Loop Optimal Transport for Unsupervised Action Segmentation},
  author  = {Bueno-Benito, Elena and Dimiccoli, Mariella},
  journal = {arXiv preprint arXiv:2608.05877},
  year    = {2026}
}
```


## Acknowledgements

This code builds on [CLOT](https://arxiv.org/abs/2507.03539) and on the [ASOT](https://github.com/mingu6/action_seg_ot) codebase.
