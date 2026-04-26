---
title: "PATCH: A Plug-in Framework of Non-blocking Inference for Distributed Multimodal Systems"
collection: portfolio
permalink: /project/patch/
category: "AI Systems"
conference: "UbiComp 2023"
order: 1
---

<div style="display:grid; grid-template-columns:1fr 1fr; gap:12px; align-items:center; width:100%;">

  <img src="/images/projects/patch_main.jpg"
       style="width:100%; max-height:260px; object-fit:contain;">

  <img src="/images/projects/patch_design.jpg"
       style="width:100%; max-height:260px; object-fit:contain;">

</div>

**Conference:** {{ page.conference }}

PATCH is a plug-in framework for non-blocking inference in distributed multimodal systems under missing, delayed, or corrupted sensor streams. It introduces cross-modality feature imputation, lightweight feature pair ranking, and data alignment modules to preserve inference accuracy and low latency without retraining the original multimodal models.

**Highlights**

- Non-blocking multimodal inference under missing or delayed sensor data  
- Plug-in framework compatible with early, intermediate, and late fusion models  
- Cross-modality feature imputation with lightweight ranking and alignment modules  
- Evaluated on nine multimodal models across autonomous driving, activity recognition, and event parsing tasks  
- Up to 13% accuracy improvement with 73% lower training overhead than retraining
