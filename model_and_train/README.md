# Mnist 模型訓練
* `define_model.py` 為模型定義程式 
* `mnist.py` 為模型訓練程式 

## 前置作業
* 建構模型訓練環境
```bash
conda create -n env_name python=3.8
conda activate env_name
```

* 安裝 pytorch、torchvision
```bash
conda install pytorch==1.8.0 torchvision==0.9.0 cpuonly -c pytorch
```

* 安裝 torchsummary、PyYAML、tqdm
```bash
pip install torchsummary PyYAML tqdm
```

## 開始訓練
* 確保 Python 執行環境為 `env_name`
* 執行 `mnist.py` 並等待即可



