<h1 align="center">
  ET-Turb: Continuous Exposure-Time Modeling<br>
  for Realistic Atmospheric Turbulence Synthesis
</h1>

<p align="center"><strong>CVPR 2026</strong></p>

<p align="center">
  Junwei Zeng &nbsp;&middot;&nbsp;
  Dong Liang &nbsp;&middot;&nbsp;
  Sheng-Jun Huang &nbsp;&middot;&nbsp;
  Kun Zhan &nbsp;&middot;&nbsp;
  Songcan Chen
</p>

<p align="center">
  Nanjing University of Aeronautics and Astronautics
  &nbsp;&nbsp;|&nbsp;&nbsp;
  Lanzhou University
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2603.01398">
    <img src="https://img.shields.io/badge/arXiv-2603.01398-b31b1b.svg?style=flat-square" alt="arXiv">
  </a>
  <a href="https://cvpr.thecvf.com/Conferences/2026">
    <img src="https://img.shields.io/badge/CVPR-2026-2ea44f.svg?style=flat-square" alt="CVPR 2026">
  </a>
  <a href="https://github.com/Jun-Wei-Zeng/ET-Turb">
    <img src="https://img.shields.io/badge/Code-GitHub-181717.svg?style=flat-square&logo=github" alt="Code">
  </a>
  <img src="https://img.shields.io/badge/Dataset-Coming%20Soon-f0ad4e.svg?style=flat-square" alt="Dataset coming soon">
</p>

---

## &#128226; News

- **March 2026:** ET-Turb was accepted by [CVPR 2026](https://cvpr.thecvf.com/Conferences/2026).
- **March 2026:** The paper was released on [arXiv](https://arxiv.org/abs/2603.01398).

> [!TIP]
> If ET-Turb helps your research, please consider giving this repository a star.

## &#128230; Dataset

> [!NOTE]
> The ET-Turb dataset will be released.

<div align="center">
<table>
  <thead>
    <tr>
      <th align="center">Videos</th>
      <th align="center">Frames</th>
      <th align="center">Training Videos</th>
      <th align="center">Test Videos</th>
      <th align="center">Exposure Time</th>
      <th align="center">Configurations</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong>5,083</strong></td>
      <td align="center"><strong>2,005,835</strong></td>
      <td align="center">3,988</td>
      <td align="center">1,095</td>
      <td align="center">0.5-40 ms</td>
      <td align="center">12</td>
    </tr>
  </tbody>
</table>
</div>

## &#128202; Results

<p align="center">
  <strong>No-Reference Evaluation on Real Turbulence</strong><br>
  <sub>Lower NIQE and BRISQUE scores are better.</sub>
</p>

<div align="center">
<table>
  <thead>
    <tr>
      <th rowspan="2" align="center">Training Dataset</th>
      <th colspan="2" align="center">TSR-WGAN</th>
      <th colspan="2" align="center">TMT</th>
      <th colspan="2" align="center">DATUM</th>
      <th colspan="2" align="center">MambaTM</th>
    </tr>
    <tr>
      <th align="center">NIQE &darr;</th>
      <th align="center">BRISQUE &darr;</th>
      <th align="center">NIQE &darr;</th>
      <th align="center">BRISQUE &darr;</th>
      <th align="center">NIQE &darr;</th>
      <th align="center">BRISQUE &darr;</th>
      <th align="center">NIQE &darr;</th>
      <th align="center">BRISQUE &darr;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">TMT-dynamic</td>
      <td align="center">4.231</td>
      <td align="center">52.502</td>
      <td align="center">4.361</td>
      <td align="center">58.581</td>
      <td align="center">4.219</td>
      <td align="center">54.921</td>
      <td align="center">4.217</td>
      <td align="center">55.062</td>
    </tr>
    <tr>
      <td align="center">ATSyn-dynamic</td>
      <td align="center">4.224</td>
      <td align="center">54.462</td>
      <td align="center">4.483</td>
      <td align="center">59.707</td>
      <td align="center">4.308</td>
      <td align="center">59.126</td>
      <td align="center">4.247</td>
      <td align="center">56.876</td>
    </tr>
    <tr>
      <td align="center">ET-Turb</td>
      <td align="center">4.190</td>
      <td align="center">50.981</td>
      <td align="center">4.221</td>
      <td align="center">56.691</td>
      <td align="center">4.204</td>
      <td align="center">54.070</td>
      <td align="center">4.212</td>
      <td align="center">55.050</td>
    </tr>
  </tbody>
</table>
</div>

## &#128221; Citation

```bibtex
@inproceedings{zeng2026continuous,
  title={Continuous Exposure-Time Modeling for Realistic Atmospheric Turbulence Synthesis},
  author={Zeng, Junwei and Liang, Dong and Huang, Sheng-Jun and Zhan, Kun and Chen, Songcan},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={26678--26687},
  year={2026}
}
```
