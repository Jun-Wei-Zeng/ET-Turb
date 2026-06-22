<h1 align="center">
  Continuous Exposure-Time Modeling<br>
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
  <a href="https://pan.baidu.com/s/1VwCyHTAuQ7TY1afF--wmgA">
    <img src="https://img.shields.io/badge/Dataset-Baidu%20Netdisk-2932E1.svg?style=flat-square" alt="Download dataset from Baidu Netdisk">
  </a>
</p>

---

## &#128226; News

- **March 2026:** ET-Turb was accepted by [CVPR 2026](https://cvpr.thecvf.com/Conferences/2026).
- **March 2026:** The paper was released on [arXiv](https://arxiv.org/abs/2603.01398).

> [!TIP]
> If ET-Turb helps your research, please consider giving this repository a star.

## &#128230; Dataset

> [!IMPORTANT]
> Download `ET_Turb.zip` from [Baidu Netdisk](https://pan.baidu.com/s/1VwCyHTAuQ7TY1afF--wmgA). Extraction code: `ba9x`.

<p align="center">
  <strong>Parameter Sampling Ranges for ET-Turb Dataset Generation</strong><br>
  <sub><code>[a,b]</code> denotes uniform sampling from a continuous interval; <code>{v1, ..., vn}</code> denotes uniform sampling from a discrete set.<br>All 12 configurations are sampled with equal probability.</sub>
</p>

<div align="center">
<table>
  <thead>
    <tr>
      <th align="center">Distance<br>(m)</th>
      <th align="center">Focal Length<br>(m)</th>
      <th align="center">F-number</th>
      <th align="center">C<sub>n</sub><sup>2</sup><br>(10<sup>-14</sup> m<sup>-2/3</sup>)</th>
      <th align="center">Height<br>(m)</th>
      <th align="center">Wind Speed<br>(m/s)</th>
      <th align="center">Exposure Time<br>(ms)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2" align="center">[30,100]</td>
      <td rowspan="2" align="center">[0.1,0.3]</td>
      <td align="center">{2.8,4}</td>
      <td align="center">[50,300]</td>
      <td align="center">{4,50}</td>
      <td align="center">[1,3]</td>
      <td align="center">[0.5,8]</td>
    </tr>
    <tr>
      <td align="center">{2.8,4,5.6}</td>
      <td align="center">[200,500]</td>
      <td align="center">{100,200}</td>
      <td align="center">[3,5]</td>
      <td align="center">[0.5,8]</td>
    </tr>
    <tr>
      <td rowspan="2" align="center">[100,200]</td>
      <td rowspan="2" align="center">[0.2,0.5]</td>
      <td align="center">{2.8,4,5.6}</td>
      <td align="center">[5,50]</td>
      <td align="center">{200,400}</td>
      <td align="center">[1,4]</td>
      <td align="center">[1,20]</td>
    </tr>
    <tr>
      <td align="center">{2.8,4,5.6,8}</td>
      <td align="center">[20,100]</td>
      <td align="center">{4,50}</td>
      <td align="center">[2,6]</td>
      <td align="center">[0.5,10]</td>
    </tr>
    <tr>
      <td rowspan="2" align="center">[200,400]</td>
      <td rowspan="2" align="center">[0.3,0.5]</td>
      <td align="center">{2.8,4,5.6,8}</td>
      <td align="center">[2,30]</td>
      <td align="center">{50,100}</td>
      <td align="center">[2,5]</td>
      <td align="center">[1,20]</td>
    </tr>
    <tr>
      <td align="center">{4,5.6,8,11}</td>
      <td align="center">[10,40]</td>
      <td align="center">{10,50}</td>
      <td align="center">[3,6]</td>
      <td align="center">[1,20]</td>
    </tr>
    <tr>
      <td rowspan="2" align="center">[400,600]</td>
      <td rowspan="2" align="center">[0.4,0.75]</td>
      <td align="center">{4,5.6,8,11}</td>
      <td align="center">[1,20]</td>
      <td align="center">{50,150}</td>
      <td align="center">[3,5]</td>
      <td align="center">[2,40]</td>
    </tr>
    <tr>
      <td align="center">{5.6,8,11,16}</td>
      <td align="center">[10,30]</td>
      <td align="center">{10,100}</td>
      <td align="center">[4,7]</td>
      <td align="center">[1,20]</td>
    </tr>
    <tr>
      <td rowspan="2" align="center">[600,800]</td>
      <td rowspan="2" align="center">[0.6,0.8]</td>
      <td align="center">{5.6,8,11,16}</td>
      <td align="center">[1,15]</td>
      <td align="center">{100,300}</td>
      <td align="center">[3,7]</td>
      <td align="center">[2,40]</td>
    </tr>
    <tr>
      <td align="center">{8,11,16,18}</td>
      <td align="center">[2,20]</td>
      <td align="center">{50,200}</td>
      <td align="center">[4,8]</td>
      <td align="center">[2,40]</td>
    </tr>
    <tr>
      <td rowspan="2" align="center">[800,1000]</td>
      <td rowspan="2" align="center">[0.8,1]</td>
      <td align="center">{8,11,16,18}</td>
      <td align="center">[0.5,10]</td>
      <td align="center">{10,100}</td>
      <td align="center">[5,9]</td>
      <td align="center">[2,40]</td>
    </tr>
    <tr>
      <td align="center">{11,16,18,24}</td>
      <td align="center">[1,20]</td>
      <td align="center">{4,50}</td>
      <td align="center">[6,10]</td>
      <td align="center">[1,20]</td>
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
