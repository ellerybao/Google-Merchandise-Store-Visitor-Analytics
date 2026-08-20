# data文件夹
此文件夹专门用于放置GMS原始数据集。

## 关于原始数据集
原始数据集因为占用内存过大，这里用Kaggle链接替代。

**Kaggle官方链接**：https://www.kaggle.com/competitions/ga-customer-revenue-prediction/data  （需注册账号加入比赛下载，部分地区存在验证限制，可能无法加入）

**备用链接（百度网盘）**：https://pan.baidu.com/s/1FMJq0zwh_b-ibDSj4S8bKw?pwd=gmsd 提取码: gmsd

下载后请解压文件，并将文件中的train.csv拖入此文件夹。

## 关于中间表（processed文件夹）

由于文件较大，`processed/` 文件夹下的2张中间表已上传至百度网盘。

**下载链接（百度网盘）**：https://pan.baidu.com/s/1P76zMhXvreEQdfeCNm1LxA?pwd=gmsp 提取码: gmsp

下载后请解压到 `data/processed/` 目录下，得到以下2个文件：

- **Cleaned_Google_Dataset.csv**：洗并展开原始JSON字段后的完整交易数据集，作为Power BI看板的事实表。

- **Customers.csv**：基于清洗后数据集提炼的访客维度表，用于Power BI看板中客户维度的分析与筛选。