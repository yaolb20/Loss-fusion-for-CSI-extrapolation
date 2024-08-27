This is the source code of the letter "Loss Function Fusion for Learning Based CSI Extrapolation Enhancement"
1. Due to storage restriction of Github, datasets, checkpoints and simulation records can be downloaded from Tsinghua Cloud:
https://cloud.tsinghua.edu.cn/d/72c4ebe4b10f4eae97b5/
2. The folder is free to use, including dataset utilization, simulation result reproduction, model improvement, etc.
3. For academic use, please cite the reference below:
L. Yao, K. Ma, et al., Loss Function Fusion for Learning Based CSI Extrapolation Enhancement, submitted to IEEE, to be uploaded in Arxiv.
4. Run `halving.py` to optimize the weight of the fused loss function by successive halving algorithm. 
Run `main.py` to train and evaluate the model. 
The loss function type could be set by modifying the corresponding lines in `main.py`. 
Run `Figure1.m`, `Figure2.m` and `Figure3.m` to generate Figure 1, 2 and 3, respectively.
