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

# TAXONOMY OF MULTI-VIEW ATTENTION
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal;text-decoration:none">\checkmark</span></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">LiteGT[30]</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SAT[32]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">NAGphormer[34]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">PPRGAT[37]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">DET[60]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">CAT[65]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">EGT[73]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GOAT[87]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SAN[88]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">INFMCS[90]</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GraphHAM[103]</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Gradformer[108]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MWGNN[122]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GraphiT[127]</td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">NI-CTR[129]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Deformable GCN[140]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GPRE[141]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">TWC-GNN[142]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ExGAT[147]</td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GTAT[161]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AM-GCN[183]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Graphormer[217]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MV-GCN[222]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Graph-Bert[228]</td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ANS-GT[236]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Gophormer[239]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">DCAT[244]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AnchorGT[246]</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>

# TAXONOMY OF HOMOGENEOUS GRAPH ATTENTION
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ESA[21]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
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
  </tr>
  <tr>
    <td class="tg-c3ow">E-ResGAT[28]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">29</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">EGAT[33]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GraphTransformer[45]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">EATSA-GNN[48]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">EGT[73]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">TokenGT[84]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SAN[88]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">UniMP[164]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Graphormer[217]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>

# TAXONOMY OF HETEROGENEOUS GRAPH ATTENTION
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">CGAT[24]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GATNE[26]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">MAGNN[50]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HetSANN[67]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HGT[69]</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HGNN-AC[77]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HG-former[102]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">HGAT[106]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">PSHGAN[125]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">NI-CTR[129]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">RelGNN[145]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">EAGCN[158]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HAN[182]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">HetGNN[225]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow">CL-GNN[245]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
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

# TAXONOMY OF GRAPH SIMILARITY
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">SimGNN[8]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">MSNA[9]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">LiteGT[30]</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">AMNS[59]</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">DET[60]</td>
    <td class="tg-c3ow">\checkmark</td>
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
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">G-Guard[71]</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">GCAN[75]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">TANGNN[76]</td>
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
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">INFMCS[90]</td>
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
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">GMN[96]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">MGMN[105]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">DeepSIM[107]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">NA-GSL[172]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">AGNN[173]</td>
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
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">180</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">MSF-GCN[184]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">CoSimGNN[203]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">PSimGNN[204]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
  </tr>
  <tr>
    <td class="tg-c3ow">SiGAT[208]</td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">\checkmark</td>
    <td class="tg-c3ow"></td>
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
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ADSF[230]</td>
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
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">ANS-GT[236]</td>
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
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody></table>

