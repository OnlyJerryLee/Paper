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
    <td class="tg-f1yk">RAW-GNN<a href="https://arxiv.org/abs/2206.13953" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">U-GCN<a href="https://proceedings.neurips.cc/paper/2021/hash/5857d68cd9280bc98d079fa912fd6740-Abstract.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">AERO-GNN<a href="https://proceedings.mlr.press/v202/lee23b.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">NLGAT<a href="https://ieeexplore.ieee.org/abstract/document/9645300" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">TGCA<a href="https://ieeexplore.ieee.org/abstract/document/10888159" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">MSAD-GNN<a href="https://link.springer.com/article/10.1007/s10115-025-02406-5" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">NAAM<a href="https://ojs.aaai.org/index.php/AAAI/article/view/35278" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">ASLAM<a href="https://www.sciencedirect.com/science/article/abs/pii/S1568494625005794" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">AGDN<a href="https://arxiv.org/abs/2012.15024" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">WRGNN<a href="https://dl.acm.org/doi/abs/10.1145/3447548.3467373" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">DAEGC<a href="https://arxiv.org/abs/1906.06532" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">MAGNA<a href="https://arxiv.org/abs/2009.14332" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">SNAN<a href="https://ieeexplore.ieee.org/abstract/document/9174790" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">NodeFormer<a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/af790b7ae573771689438bbcfc5933fe-Abstract-Conference.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">SAGNN<a href="https://www.sciencedirect.com/science/article/abs/pii/S0925231223008548" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">GraphTrans<a href="https://proceedings.neurips.cc/paper/2021/hash/6e67691b60ed3e4a55935261314dd534-Abstract.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">SPAGAN<a href="https://arxiv.org/abs/2101.03464" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">Graph-Bert<a href="https://arxiv.org/abs/2001.05140" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">Graph Transformer<a href="https://ojs.aaai.org/index.php/AAAI/article/view/6243" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">LiteGT<a href="https://dl.acm.org/doi/abs/10.1145/3459637.3482272" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">SAT<a href="https://proceedings.mlr.press/v162/chen22r" target="_blank">[Link]</a></td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-f1yk">DET<a href="https://arxiv.org/abs/2202.10581" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">CAT<a href="https://proceedings.neurips.cc/paper/2021/hash/1587965fb4d4b5afe8428a4a024feb0d-Abstract.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">EGT<a href="https://dl.acm.org/doi/abs/10.1145/3534678.3539296" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">U-GCN<a href="https://proceedings.neurips.cc/paper/2021/hash/5857d68cd9280bc98d079fa912fd6740-Abstract.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">GOAT<a href="https://proceedings.mlr.press/v202/kong23a.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">SAN<a href="https://proceedings.neurips.cc/paper_files/paper/2021/hash/b4fd1d2cb085390fbbadae65e07876a7-Abstract.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">INFMCS<a href="https://ieeexplore.ieee.org/abstract/document/10496270" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">AERO-GNN<a href="https://proceedings.mlr.press/v202/lee23b.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">GraphHAM<a href="https://dl.acm.org/doi/abs/10.1145/3488560.3498499" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">Gradformer<a href="https://arxiv.org/abs/2404.15729" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">MWGNN<a href="https://dl.acm.org/doi/abs/10.1145/3485447.3512100" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">GraphiT<a href="https://arxiv.org/abs/2106.05667" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">NI-CTR<a href="https://dl.acm.org/doi/abs/10.1145/3477495.3532031" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">Deformable GCN<a href="https://ojs.aaai.org/index.php/AAAI/article/view/20765" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">GPRE<a href="https://arxiv.org/abs/2201.12787" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">TWC-GNN<a href="https://www.nature.com/articles/s41598-024-84816-z" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">ExGAT<a href="https://www.sciencedirect.com/science/article/abs/pii/S0893608024007081" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">GTAT<a href="https://www.nature.com/articles/s41598-025-88993-3" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">AM-GCN<a href="https://dl.acm.org/doi/abs/10.1145/3394486.3403177" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">Graphormer<a href="https://proceedings.neurips.cc/paper/2021/hash/f1c1592588411002af340cbaedd6fc33-Abstract.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">MV-GCN<a href="https://dl.acm.org/doi/abs/10.1145/3459637.3482477" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">Graph-Bert<a href="https://arxiv.org/abs/2001.05140" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">ANS-GT<a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/854a9ab0f323b841955e70ca383b27d1-Abstract-Conference.html" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">Gophormer<a href="https://arxiv.org/abs/2110.13094" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">DCAT<a href="https://ieeexplore.ieee.org/abstract/document/10428085" target="_blank">[Link]</a></td>
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
    <td class="tg-f1yk">AnchorGT<a href="https://arxiv.org/abs/2405.03481" target="_blank">[Link]</a></td>
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


