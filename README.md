### 工程结构说明
- code_first
  1. 包含ResNet模型代码
- data_zip/data
  1. 数据文件，包括训练集和测试集
  - training.zip：包含训练中的图片和标签
  - validation.zip：包含验证集的图片
  - valid_gt.zip：包含验证集的标签
  2. ex:
  - 病理性近视（PM）：文件名以P开头
  - 非病理性近视（non-PM）：
  - 高度近似（high myopia）：文件名以H开头
  - 正常眼睛（normal）：文件名以N开头
