# ⚡FlashMesh: Faster and Better Autoregressive Mesh Synthesis via Structured Speculation

This is the repository that contains source code for the [FlashMesh website](https://FlashMesh.github.io).

## Project Status

### Completed
- ✅ Title -- Completed
- ✅ Authors -- Completed  
- ✅ Institutions -- Completed
- ✅ Buttons -- Completed
- ✅ Abstract -- Completed

### TODO
- 🔄 Teaser -- TODO
- 🔄 Architecture Diagram -- TODO
- 🔄 Architecture GIF -- TODO
- 🔄 Demo Video -- TODO
- 🔄 3D OBJ Visualization -- TODO
- 🔄 Comparison -- TODO

## Abstract

Autoregressive models can generate high-quality 3D meshes by sequentially producing vertices and faces, but their token-by-token decoding results in slow inference, limiting practical use in interactive and large-scale applications. We present FlashMesh, a fast and high-fidelity mesh generation framework that rethinks autoregressive decoding through a predict-correct-verify paradigm. The key insight is that mesh tokens exhibit strong structural and geometric correlations that enable confident multi-token speculation. FlashMesh leverages this by introducing a speculative decoding scheme tailored to the commonly used hourglass transformer architecture, enabling parallel prediction across face, point, and coordinate levels. Extensive experiments show that FlashMesh achieves up to a 2x speedup over standard autoregressive models while also improving generation fidelity. Our results demonstrate that structural priors in mesh data can be systematically harnessed to accelerate and enhance autoregressive generation.

## Authors
- Tingrui Shen (South China University of Technology)
- Yiheng Zhang (National University of Singapore) 
- Chen Tang (South China University of Technology)
- Chuan Ping (Zhejiang University)
- Zixing Zhao (Tencent)
- Le Wan (Tencent)
- Yuwang Wang (Tsinghua University)
- Ronggang Wang (Peking University)
- Shengfeng He (Singapore Management University)

## Citation

If you find FlashMesh useful for your work please cite: 
```
@article{shen2026flashmesh,
author = {Shen, Tingrui and Zhang, Yiheng and Tang, Chen and Ping, Chuan and Zhao, Zixing and Wan, Le and Wang, Yuwang and Wang, Ronggang and He, Shengfeng},
title = {FlashMesh: Faster and Better Autoregressive Mesh Synthesis via Structured Speculation},
journal = {CVPR},
year = {2026},
}
```

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
