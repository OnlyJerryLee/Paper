# Paper
This is the repository for the collection of Graph-based Deep Learning for Communication Networks.

If you find this repository helpful, you may consider cite our relevant work:


# Taxonomy Of Local Attention
<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow" colspan="2">Graph</th>
    <th class="tg-c3ow" colspan="3"><span style="font-weight:400;font-style:normal">Embedding</span></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Scope</span></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Head</span></th>
    <th class="tg-c3ow" colspan="4"><span style="font-weight:400;font-style:normal">Task</span></th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-c3ow">Model</td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Homogeneous</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Heterogeneous</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Node</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Edge</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Graph</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Neighbor</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Multi-Hop</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Single</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Multi</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Node </span><br><span style="font-weight:400;font-style:normal">Classification</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Link </span><br><span style="font-weight:400;font-style:normal">Prediction</span></td>
    <td class="tg-c3ow">Graph <br>Classification</td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Graph </span><br><span style="font-weight:400;font-style:normal">Regression</span></td>
  </tr>
  <tr>
    <td class="tg-f1yk">FAGCN<a href="https://ojs.aaai.org/index.php/AAAI/article/view/16514" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"> </td>
  </tr>
  <tr>
    <td class="tg-f1yk">GATv2<a href="https://arxiv.org/abs/2105.14491" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-f1yk">HGCN<a href="https://proceedings.neurips.cc/paper_files/paper/2019/hash/0415740eaa4d9decbc8da001d3fd805f-Abstract.html" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">PPRGAT<a href="https://ieeexplore.ieee.org/abstract/document/9746788" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">ACEHGNN<a href="https://ieeexplore.ieee.org/abstract/document/9679192" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal;text-decoration:none">✓</span></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">hGAO<a href="https://dl.acm.org/doi/abs/10.1145/3292500.3330897" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">PMP-GAT<a href="https://www.sciencedirect.com/science/article/pii/S0004370224000651" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">SATs<a href="https://arxiv.org/abs/2210.07715" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">U-GCN<a href="https://proceedings.neurips.cc/paper/2021/hash/5857d68cd9280bc98d079fa912fd6740-Abstract.html" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">SuperGAT<a href="https://arxiv.org/abs/2204.04879" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-f1yk">GeniePath<a href="https://ojs.aaai.org/index.php/AAAI/article/view/4354" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">UGformer<a href="https://dl.acm.org/doi/abs/10.1145/3487553.3524258" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">HA-GNN<a href="https://link.springer.com/article/10.1007/s00521-024-09689-9" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">GAT<a href="https://arxiv.org/abs/1710.10903" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">C-GAT<a href="https://arxiv.org/abs/1910.11945" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk"><a href="https://arxiv.org/abs/2103.13355" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">RFA-GNN<a href="https://ieeexplore.ieee.org/abstract/document/10011169" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">SAGNN<a href="https://www.sciencedirect.com/science/article/pii/S0925231223008548" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">DMP<a href="https://proceedings.neurips.cc/paper/2021/hash/253614bbac999b38b5b60cae531c4969-Abstract.html" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">𝜅HGCN<a href="https://dl.acm.org/doi/abs/10.1145/3580305.3599532" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">FactorGCN<a href="https://proceedings.neurips.cc/paper/2020/hash/ea3502c3594588f0e9d5142f99c66627-Abstract.html?ref=https://githubhelp.com" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">CDP-GA<a href="https://ieeexplore.ieee.org/abstract/document/9378189/" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">SGAT<a href="https://ieeexplore.ieee.org/abstract/document/9399811" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">GMKEA<a href="https://www.sciencedirect.com/science/article/pii/S095070512100561X" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">CPA<a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7416665/" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">HAT<a href="https://ieeexplore.ieee.org/abstract/document/9435103" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>



# TAXONOMY OF HIGH-ORDER ATTENTION
<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow" colspan="2">Graph</th>
    <th class="tg-c3ow" colspan="3">Embedding</th>
    <th class="tg-c3ow" colspan="2">Scope</th>
    <th class="tg-c3ow" colspan="2">Head</th>
    <th class="tg-c3ow" colspan="4">Task</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Model</span></td>
    <td class="tg-c3ow">Homogeneous</td>
    <td class="tg-c3ow">Heterogeneous</td>
    <td class="tg-c3ow">Node</td>
    <td class="tg-c3ow">Edge</td>
    <td class="tg-c3ow">Graph</td>
    <td class="tg-c3ow">Neighbor</td>
    <td class="tg-c3ow">Multi-Hop</td>
    <td class="tg-c3ow">Single</td>
    <td class="tg-c3ow">Multi</td>
    <td class="tg-c3ow">Node <br>Classification</td>
    <td class="tg-c3ow">Node <br>cluster</td>
    <td class="tg-c3ow">Link <br>Prediction</td>
    <td class="tg-c3ow"><span style="color:black">Graph </span><br><span style="color:black">Classification</span></td>
  </tr>
  <tr>
    <td class="tg-f1yk">DMG<a href="https://ieeexplore.ieee.org/abstract/document/11114958" target="_blank">[Link]</a></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">NAGphormer<a href="https://arxiv.org/abs/2206.04910" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">HopGNN<a href="https://openaccess.thecvf.com/content/CVPR2023/html/Chen_From_Node_Interaction_To_Hop_Interaction_New_Effective_and_Scalable_CVPR_2023_paper.html" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">RAW-GNN<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">U-GCN<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-f1yk">AERO-GNN<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">NLGAT<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">GeniePath<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">TGCA<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">MSAD-GNN<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">NAAM<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">ASLAM<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">AGDN<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">WRGNN<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">DAEGC<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">MAGNA<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">SNAN<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">NodeFormer<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">SAGNN<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">GraphTrans<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-f1yk">SPAGAN<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">Graph-Bert<a href="" target="_blank">[Link]</a></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>



# TAXONOMY OF MULTI-VIEW ATTENTION
<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Graph</span></th>
    <th class="tg-c3ow" colspan="3">Embedding</th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Scope</span></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Head</span></th>
    <th class="tg-c3ow" colspan="6"><span style="font-weight:400;font-style:normal">Task</span></th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-c3ow">Model</td>
    <td class="tg-c3ow">Homogeneous</td>
    <td class="tg-c3ow">Heterogeneous</td>
    <td class="tg-c3ow">Node</td>
    <td class="tg-c3ow">Edge</td>
    <td class="tg-c3ow">Graph</td>
    <td class="tg-c3ow">Neighbor</td>
    <td class="tg-c3ow">Multi-Hop</td>
    <td class="tg-c3ow">Single</td>
    <td class="tg-c3ow">Multi</td>
    <td class="tg-c3ow">Node <br>Classification</td>
    <td class="tg-c3ow">Edge <br>Classification</td>
    <td class="tg-c3ow">Link <br>Prediction</td>
    <td class="tg-c3ow">Graph <br>Classification</td>
    <td class="tg-c3ow">Graph <br>Regression</td>
    <td class="tg-c3ow">Other</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Graph Transformer[23]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">LiteGT[30]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SAT[32]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">NAGphormer[34]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">PPRGAT[37]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">DET[60]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">CAT[65]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">EGT[73]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">U-GCN[79]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GOAT[87]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SAN[88]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">INFMCS[90]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AERO-GNN[93]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GraphHAM[103]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Gradformer[108]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MWGNN[122]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GraphiT[127]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">NI-CTR[129]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Deformable GCN[140]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GPRE[141]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">TWC-GNN[142]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ExGAT[147]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GTAT[161]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AM-GCN[183]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Graphormer[217]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MV-GCN[222]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Graph-Bert[228]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ANS-GT[236]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Gophormer[239]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">DCAT[244]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AnchorGT[246]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>



# TAXONOMY OF HOMOGENEOUS GRAPH ATTENTION
<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Graph</span></th>
    <th class="tg-c3ow" colspan="3">Embedding</th>
    <th class="tg-c3ow" colspan="2">Scope</th>
    <th class="tg-c3ow" colspan="2">Head</th>
    <th class="tg-c3ow" colspan="5">Task</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Model</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Homogeneous</span></td>
    <td class="tg-c3ow">Heterogeneous</td>
    <td class="tg-c3ow">Node</td>
    <td class="tg-c3ow">Edge</td>
    <td class="tg-c3ow">Graph</td>
    <td class="tg-c3ow">Neighbor</td>
    <td class="tg-c3ow">Multi-Hop</td>
    <td class="tg-c3ow">Single</td>
    <td class="tg-c3ow">Multi</td>
    <td class="tg-c3ow">Node Classification</td>
    <td class="tg-c3ow">Edge Classification</td>
    <td class="tg-c3ow">Graph Classification</td>
    <td class="tg-c3ow">Graph Regression</td>
    <td class="tg-c3ow">Other</td>
  </tr>
  <tr>
    <td class="tg-c3ow">MemGNN[1]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ESA[21]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">E-ResGAT[28]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">29</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">EGAT[33]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GraphTransformer[45]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">EATSA-GNN[48]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">EGT[73]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">TokenGT[84]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SAN[88]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">UniMP[164]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Graphormer[217]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>


# TAXONOMY OF HETEROGENEOUS GRAPH ATTENTION
<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Graph</span></th>
    <th class="tg-c3ow" colspan="3"><span style="font-weight:400;font-style:normal">Embedding</span></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Scope</span></th>
    <th class="tg-c3ow" colspan="2">Head</th>
    <th class="tg-c3ow" colspan="7"><span style="font-weight:400;font-style:normal">Task</span></th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-c3ow">Model</td>
    <td class="tg-c3ow">Homogeneous</td>
    <td class="tg-c3ow">Heterogeneous</td>
    <td class="tg-c3ow">Node</td>
    <td class="tg-c3ow">Edge</td>
    <td class="tg-c3ow">Graph</td>
    <td class="tg-c3ow">Neighbor</td>
    <td class="tg-c3ow">Multi-Hop</td>
    <td class="tg-c3ow">Single</td>
    <td class="tg-c3ow">Multi</td>
    <td class="tg-c3ow">Node <br>Classification</td>
    <td class="tg-c3ow">Node <br>cluster</td>
    <td class="tg-c3ow">Edge <br>Classification</td>
    <td class="tg-c3ow">Link <br>Prediction</td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Graph </span><br><span style="font-weight:400;font-style:normal">Classification</span></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Graph </span><br>Regression</td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Other</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GraphTransformer[23]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">CGAT[24]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GATNE[26]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MAGNN[50]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HetSANN[67]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HGT[69]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HGNN-AC[77]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HG-former[102]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">HGAT[106]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Simple-HGN[118]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">PSHGAN[125]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">NI-CTR[129]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">RelGNN[145]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">EAGCN[158]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HAN[182]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HetGNN[225]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">CL-GNN[245]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>


# TAXONOMY OF KNOWLEDGE GRAPH ATTENTION
<table class="tg"><thead>
  <tr>
    <th class="tg-r80l"></th>
    <th class="tg-r80l" colspan="2">Graph</th>
    <th class="tg-r80l" colspan="3">Embedding</th>
    <th class="tg-f1yk" colspan="2"><span style="font-weight:400;font-style:normal">Scope</span></th>
    <th class="tg-f1yk" colspan="2"><span style="font-weight:400;font-style:normal">Head</span></th>
    <th class="tg-f1yk" colspan="7">Task</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-r80l">Model</td>
    <td class="tg-r80l">Homogeneous</td>
    <td class="tg-r80l">Heterogeneous</td>
    <td class="tg-r80l"><span style="font-weight:400;font-style:normal">Node</span></td>
    <td class="tg-r80l"><span style="font-weight:400;font-style:normal">Edge</span></td>
    <td class="tg-r80l"><span style="font-weight:400;font-style:normal">Graph</span></td>
    <td class="tg-42x8"><span style="font-weight:400;font-style:normal">Neighbor</span></td>
    <td class="tg-42x8"><span style="font-weight:400;font-style:normal">Multi-Hop</span></td>
    <td class="tg-42x8"><span style="font-weight:400;font-style:normal">Single</span></td>
    <td class="tg-42x8">Multi</td>
    <td class="tg-vlxe">Node Classification</td>
    <td class="tg-vlxe">Link Prediction</td>
    <td class="tg-vlxe">Graph Classification</td>
    <td class="tg-42x8">knowledge graph<br><span style="font-weight:400;font-style:normal">completion</span></td>
    <td class="tg-vlxe">Entity Alignment</td>
    <td class="tg-42x8">Comparative preference<br><span style="font-weight:400;font-style:normal">classification</span></td>
    <td class="tg-42x8">Recommendation</td>
  </tr>
  <tr>
    <td class="tg-f1yk">RGHAT<a href="https://your-link-here" target="_blank">[Link]</a></td>
    <td class="tg-r80l"></td>
    <td class="tg-r80l">✓</td>
    <td class="tg-r80l">✓</td>
    <td class="tg-r80l"></td>
    <td class="tg-r80l"><span style="font-weight:400;font-style:normal;text-decoration:none">✓</span></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-r80l">MuGNN</td>
    <td class="tg-r80l"></td>
    <td class="tg-r80l">✓</td>
    <td class="tg-r80l">✓</td>
    <td class="tg-r80l"></td>
    <td class="tg-r80l"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-zd42"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">MRGAT</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-zd42"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">HRAN</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">ED-GAT</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-zd42"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">[133]</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-zd42"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">AliNet</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-zd42"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">MAGNA</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-zd42"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">KGAT</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
  </tr>
  <tr>
    <td class="tg-f1yk">GATH</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">DisenKGAT</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">RDGCN</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">RGHAT</td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-f1yk">✓</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
</tbody></table>

# TAXONOMY OF GRAPH POOLING
<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow" colspan="2">Graph</th>
    <th class="tg-c3ow" colspan="3">Embedding</th>
    <th class="tg-c3ow" colspan="2">Scope</th>
    <th class="tg-c3ow" colspan="2">Head</th>
    <th class="tg-c3ow" colspan="5">Task</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-c3ow">Model</td>
    <td class="tg-c3ow">Homogeneous</td>
    <td class="tg-c3ow">Heterogeneous</td>
    <td class="tg-c3ow">Node</td>
    <td class="tg-c3ow">Edge</td>
    <td class="tg-c3ow">Graph</td>
    <td class="tg-c3ow">Neighbor</td>
    <td class="tg-c3ow">Multi-Hop</td>
    <td class="tg-c3ow">Single</td>
    <td class="tg-c3ow">Multi</td>
    <td class="tg-c3ow">Node <br>Classification</td>
    <td class="tg-c3ow">Node <br>Cluster</td>
    <td class="tg-c3ow">Graph <br>Classification</td>
    <td class="tg-c3ow">Graph <br>Regression</td>
    <td class="tg-c3ow">Graph <br>Similarity</td>
  </tr>
  <tr>
    <td class="tg-c3ow">MemGNN[1]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GMT[7]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MSNA[9]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ESA[21]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">RGCNN[44]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">StructSa[47]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">LookHops[53]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AttPool[70]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GOAT[87]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SAGPool[92]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HGPSACA[99]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Gapformer[109]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SMIP[112]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HAP[113]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">ABDPool[114]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">LaPool[136]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">CGIPool[137]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AGCN[143]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ASAP[149]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">DAEGC[177]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GMAPS[185]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SoPool[187]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GraphTrans[197]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AGCN[200]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GMCAP[206]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MAC[207]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">StructPool[221]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GSAPool[231]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HGP-SL[234]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal;text-decoration:none">\checkmark</span></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ENADPool[240]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>




# TAXONOMY OF GRAPH SIMILARITY
<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Graph</span></th>
    <th class="tg-c3ow" colspan="3"><span style="font-weight:400;font-style:normal">Embedding</span></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Scope</span></th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">Head</span></th>
    <th class="tg-c3ow" colspan="5"><span style="font-weight:400;font-style:normal">Task</span></th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-c3ow">Model</td>
    <td class="tg-c3ow">Homogeneous</td>
    <td class="tg-c3ow">Heterogeneous</td>
    <td class="tg-c3ow">Node</td>
    <td class="tg-c3ow">Edge</td>
    <td class="tg-c3ow">Graph</td>
    <td class="tg-c3ow">Neighbor</td>
    <td class="tg-c3ow">Multi-Hop</td>
    <td class="tg-c3ow">Single</td>
    <td class="tg-c3ow">Multi</td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">Node </span><br><span style="font-weight:400;font-style:normal">Classification</span></td>
    <td class="tg-c3ow">Link<br>Prediction</td>
    <td class="tg-c3ow">Graph <br>Classification</td>
    <td class="tg-c3ow">Graph <br>Regression</td>
    <td class="tg-c3ow">Graph <br>Similarity</td>
  </tr>
  <tr>
    <td class="tg-c3ow">DDGK[5]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SimGNN[8]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">MSNA[9]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">LiteGT[30]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AMNS[59]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">DET[60]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">G-Guard[71]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GCAN[75]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">TANGNN[76]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">INFMCS[90]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">GMN[96]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">MGMN[105]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">DeepSIM[107]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">NA-GSL[172]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">AGNN[173]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">180</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">MSF-GCN[184]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">CoSimGNN[203]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">PSimGNN[204]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
  </tr>
  <tr>
    <td class="tg-c3ow">SiGAT[208]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">CDP-GA[215]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ADSF[230]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ANS-GT[236]</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow" align="center">✓</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>


