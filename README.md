
Table 1. Effect of inserting FAEM at different CLIP layers.
| Layers | CDF-v1 | CDF-v2 | DFDC | DFDCP | DFD | Avg. |
|:-------|-------:|-------:|-----:|------:|----:|-----:|
| 1/2 | **0.8801** | 0.8661 | 0.8222 | 0.8885 | 0.9172 | 0.8748 |
| 6/7 | 0.8607 | **0.8694** | **0.8347** | **0.8921** | **0.9309** | **0.8776** |
| 23/24 | 0.8206 | 0.8407 | 0.8137 | 0.8747 | 0.9199 | 0.8539 |


<div align="left">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/87e52b94-b17c-44d7-a746-bd0ea9efdd97" width="100%" alt="Real">
        <br>
        <em>(a) Real</em>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/79e235d8-c170-47b3-abba-c7f178e8c2c1" width="100%" alt="Fake">
        <br>
        <em>(b) Fake</em>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/a1f9478f-deae-4260-9acd-7eed9724ac47" width="100%" alt="Diff_Mask">
        <br>
        <em>(c) Diff_Mask</em>
      </td>
    </tr>
  </table>

  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/3f1e6abf-2e8c-4805-9ee1-04d713704ac3" width="100%" alt="CLIP">
        <br>
        <em>(d) CLIP</em>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/cb53e273-0c20-4248-a9d7-65cc38cbb5b0" width="100%" alt="Ours">
        <br>
        <em>(e) Ours</em>
      </td>
    </tr>
  </table>
  <p><em>Figure 1. The first row shows visualizations of local inconsistencies between real and fake images, while the second row presents Grad-CAM visualizations for baseline CLIP and our method. Our adapter-guided strategy effectively directs CLIP to focus on local forgery artifacts.</em></p>
</div>
