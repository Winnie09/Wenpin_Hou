To align the photo on the left and the description on the right, you can use HTML and CSS. Here's an updated version of your R Markdown file that should achieve this layout:

```markdown
---
layout: page
title: "People"
---

### Lab Members

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="../images/woneuih11.jpg" alt="Won Eui Hong" style="width: 100px; margin-right: 20px;">
  <div>
    <strong>Won Eui Hong</strong>, Ph.D. <br/>
    Postdoctoral Researcher specializing in modeling gene regulatory networks using single-cell multiomics data. Holds a Ph.D. in Mathematical Sciences from Carnegie Mellon University, focusing on asymptotic behaviors of dynamical systems, variational techniques, and optimizations.
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
   <img src="../images/Jingyi_Yao.png" alt="Jingyi Yao" style="width: 100px; margin-right: 20px;">
  <div>
    <strong>Jingyi Yao</strong>, BSc. <br/>
    MSc Student (Y2022-2024, Theory and Methods track) in Biostatistics developing methods for integrative analysis of single-cell genomics and spatial transcriptomics data. Tow Doctoral Scholars Pilot Program nominee.
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="../images/Aiying_Huang.png" alt="Aiying Huang" style="width: 100px; margin-right: 20px;">
  <div>
    <strong>Aiying Huang</strong>, BSc. <br/>
    MSc Student (Y2023-2025, Public Health Data Science track) in Biostatistics developing statistical methods for multi-sample single-cell transcriptomics data.
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="../images/Yifei_Zhao.png" alt="Yifei Zhao" style="width: 100px; margin-right: 20px;">
  <div>
    <strong>Yifei Zhao</strong>, BSc. <br/>
    MSc Student (Y2022-2024, Theory and Methods track) in Biostatistics developing machine learning models for gene expression and DNA methylation.
  </div>
</div>

### Alumni

**Wenhan Bao**, BSc. MSc. (Y2021-2023, Theory and Methods track). PhD student at Florida University.<br/>

**Tianchuan Gao**, BSc. MSc.(Y2021-2023, Theory and Methods track). PhD student at Indiana University–Purdue University Indianapolis (IUPUI). <br/>
```

This code uses a `div` element with `display: flex;` for each lab member, which aligns the image and the description side by side. The `align-items: center;` ensures that the image and text are vertically centered relative to each other, and `margin-right: 20px;` adds some space between the image and the description. You can adjust the `margin-bottom: 20px;` to control the space between each lab member entry.
