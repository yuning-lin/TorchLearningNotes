## 安裝步驟
1. [前往 PyTorch 官網觀察可使用的 CUDA 版本](https://pytorch.org/get-started/locally/)
    * 依個人喜好選擇安裝套件的方式，conda、pip 都是推薦的使用方式

    ![](https://github.com/yuning-lin/TorchLearningNotes/blob/main/Pictures/pytorch_installation_cmd.PNG)

2. [前往 NVIDIA 下載 PyTorch 支援的 CUDA 版本](https://developer.nvidia.com/cuda-downloads)，若最新版本不符，[則前往下載先前版本](https://developer.nvidia.com/cuda-toolkit-archive)
    * 從上圖可以看到當前 PyTorch 支援的 CUDA 版本為：10.2
    * 從下圖可以看到最新的版本為：11.5
    * 故點選 Resources > Archive of Previous CUDA Releases > CUDA Toolkit 10.2，以前往下載 10.2 版

    ![](https://github.com/yuning-lin/TorchLearningNotes/blob/main/Pictures/pytorch_installation_cuda_other_version.PNG)

3. 安裝好 CUDA 後，開啟 CMD 激活虛擬環境後鍵入 PyTorch 官網建議指令
    * EX：`pip3 install torch==1.10.1+cu102 torchvision==0.11.2+cu102 torchaudio===0.10.1+cu102 -f https://download.pytorch.org/whl/cu102/torch_stable.html`
      
    ![](https://github.com/yuning-lin/TorchLearningNotes/blob/main/Pictures/pytorch_installation_cmd.PNG)
      
#### 補充
* Mac 目前僅支援 CPU；LINUX、WINDOWS 則是 CPU、GPU 都有支援
* CUDA 是一開發環境讓 GPU 可以有高性能表現
  
## 示範環境
|軟體|版本|
|:---|:---|
|Python|3.6|
|PyTorch|1.10.1|
|Windows|10|
|CUDA|10.2|


