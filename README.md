# EEG 数据处理学习记录

这是我用来学习 EEG 信号处理和分析的代码仓库。目前主要在尝试使用 Python (MNE) 读取和预处理 正常提取的EEG 的数据。

## ⚠️ 注意事项
- **数据文件**：由于数据较大，`data/` 文件夹已被 git 忽略。
- **运行方式**：如果你克隆了这个仓库，请自己下载数据集，并把 相关 `EEG` 文件放到 `data/` 目录下。

## 文件说明
- `read_eeg.ipynb`: 主要是测试读取文件，查看原始波形。
- `demo.py` / `test.py`: 临时的测试脚本。

## 环境依赖
- Python 3.9
- MNE-Python
- NumPy, Matplotlib
