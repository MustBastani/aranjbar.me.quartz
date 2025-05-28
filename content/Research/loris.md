---
title: Loris
date: 2025-05-27
---
## Stateful Analysis and Fuzzing of Commercial Baseband Firmware
![[112aa4d5b2bd6d853d4c6531719bc7a165da29342b7c2e1824d38cec4c0a2f15.jpg]]
Baseband firmware plays a critical role in cellular communication, yet its proprietary, closed-source nature and complex, stateful processing logic make systematic security testing challenging. Existing methods often fail to account for the interdependencies between baseband tasks and the statefulness of input processing logic, limiting their scope and effectiveness. We present Loris, a stateful fuzz testing framework designed to explore and analyze baseband firmware implementations effectively. We employ iterative symbolic analysis to progressively identify state variables and the predicates over them that define different protocol states, while alleviating the state explosion problem. It enables Loris to perform targeted exploration and fuzzing of program regions with high potential for vulnerabilities. We evaluated Loris across 5 commercial devices from two major vendors, covering both 4G Long-Term Evolution (LTE) and 5G New Radio (NR), demonstrating its broad applicability. Our testing revealed 7 new vulnerabilities exploitable by over-the-air attackers, potentially leading to baseband crashes, remote code execution, and denial of service.
### BibTeX
```bibtex
@INPROCEEDINGS{ranjbar_loris_2025,
  author = { Ranjbar, Ali and Yang, Tianchang and Tu, Kai and Khalilollahi, Saaman and Hussain, Syed Rafiul },
  booktitle = { 2025 IEEE Symposium on Security and Privacy (SP) },
  title = {{ Stateful Analysis and Fuzzing of Commercial Baseband Firmware }},
  year = {2025},
  ISSN = {2375-1207},
  pages = {1120-1139},
  doi = {10.1109/SP61157.2025.00143},
  url = {https://doi.ieeecomputersociety.org/10.1109/SP61157.2025.00143},
  publisher = {IEEE Computer Society},
  address = {Los Alamitos, CA, USA},
  month = May
}
```

<style> .buttons th { background: #393639; } </style>
<div class="buttons">

| [<img style="width:1.2em; height:1.3em; vertical-align:text-bottom; margin:0; padding:0;" src="9d453ce7da958b3b237ce1c2fc9a23a366cc61d724da0cd46d4537c1f49b3573.png" alt="PDF"> Paper](https://syed-rafiul-hussain.github.io/wp-content/uploads/2025/05/Loris_baseband_fuzzing_sp25.pdf) | [<img style="width:1.3em; height:1.3em; vertical-align:text-bottom; margin:0; padding:0;" src="d83ddf4ea98e9d2e77848869cbe5f0ecabb3058ede22c681bbe07b45a9091909.png" alt="GH"> Code](https://github.com/SyNSec-den/Loris) |
| :---: | :---: |

</div>