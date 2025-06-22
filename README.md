# run_workflow_in_kaggle
---
[![Milti stage Kaggle Pipeline with Dynamic Kernel IDs](https://github.com/AllieUbisse/run_workflow_in_kaggle/actions/workflows/multi-stage-kaggle-pipeline.yml/badge.svg)](https://github.com/AllieUbisse/run_workflow_in_kaggle/actions/workflows/multi-stage-kaggle-pipeline.yml)

![Drawing board](https://isquarelab-draw.onrender.com/#room=b489c999781d89afb385,-3JKfkm5dDks-hBjb85Lkg)
<br>
![image](https://github.com/user-attachments/assets/b9a03038-9b4f-40f6-97cc-5cfd2b763939)

# Limitations:
  -  This workflow is a work in progress, we main to automate running workloads in Kaggle resources.
  -  Kaggle AUTH: `Setup your Kaggle Account secrets (KAGGLE_USERNAME, KAGGLE_TOKEN), under Github Action secrets`
Kernel push error: Maximum batch CPU session count of 5 reached.

### Github Action run: single-notebook-kaggle-pipeline.yml
```
Run for STAGE in $STAGES; do
🔧 Processing stage: preprocessing
📌 Kernel ID: ***/preprocessing-pipeline-20250622095425-6d9329
Kernel version 1 successfully pushed.  Please check progress at https://www.kaggle.com/code/***/preprocessing-pipeline-20250622095425-6d9329
⏳ Kernel status: RUNNING --> ***/preprocessing-pipeline-20250622095425-6d9329 has status "KernelWorkerStatus.RUNNING"
⏳ Kernel status: RUNNING --> ***/preprocessing-pipeline-20250622095425-6d9329 has status "KernelWorkerStatus.RUNNING"
⏳ Kernel status: RUNNING --> ***/preprocessing-pipeline-20250622095425-6d9329 has status "KernelWorkerStatus.RUNNING"
⏳ Kernel status: RUNNING --> ***/preprocessing-pipeline-20250622095425-6d9329 has status "KernelWorkerStatus.RUNNING"
⏳ Kernel status: COMPLETE --> ***/preprocessing-pipeline-20250622095425-6d9329 has status "KernelWorkerStatus.COMPLETE"
```