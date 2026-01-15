# Paper
This is the repository for the collection of Graph-based Deep Learning for Communication Networks.

If you find this repository helpful, you may consider cite our relevant work:



# Node
Jianping W, Guangqiu Q, Chunming W, et al. Federated learning for network attack detection using attention-based graph neural networks[J]. Scientific Reports, 2024, 14(1): 19088.  ([Link](https://ieeexplore.ieee.org/abstract/document/11054292))

# TAXONOMY OF LOCAL ATTENTION
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
</style>
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
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">FAGCN</span>[14]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal;text-decoration:none">\checkmark</span></td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"> </td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"> </td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">GATv2</span>[16]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">HGCN</span>[27]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">PPRGAT</span>[37]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">ACEHGNN</span>[49]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal;text-decoration:none">\checkmark</span></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">hGAO</span>[51]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">PMP-GAT[64]</span></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">SATs[66]</span></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">U-GCN[79]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SuperGAT[83]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">GeniePath[115]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">UGformer[133]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HA-GNN[146]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GAT[175]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">C-GAT[178]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">186</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">RFA-GNN[193]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SAGNN[195]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">DMP[210]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">𝜅</span>HGCN[212]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">FactorGCN[213]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">CDP-GA[215]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SGAT[216]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GMKEA[226]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">CPA[232]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HAT [233]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>

# TAXONOMY OF HIGH-ORDER ATTENTION

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
</style>
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
    <td class="tg-c3ow">DMG[12]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="color:black">NAGphormer[34]</span></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HopGNN[35]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">RAW-GNN[78]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">U-GCN[79]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">AERO-GNN[93]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">NLGAT[111]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GeniePath[115]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">TGCA[116]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MSAD-GNN[119]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">NAAM[131]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ASLAM[134]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AGDN[167]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">WRGNN[171]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">DAEGC[177]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MAGNA[179]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SNAN[188]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">NodeFormer[194]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SAGNN[195]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GraphTrans[197]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">SPAGAN[214]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Graph-Bert[228]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
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
