
## ccks数据增强

1. done  
  * role中word替换  
  * 句子拼接  
  * 词mask，生成新词替换原有词  
  
2. todo:  
  * 同义词替换  
  * 依存句法分析规则  
  * 加燥处理  

### requirements
```
pip install -r requirements.txt
```

### usage
1.改写/config/config.py中的配置及dataset文件夹中相关配置文件  
2.执行main.py  
```
python main.py
```  

### 代码主要功能
1.数据分析 参考config/statistic.py及可视化文件config/eda.ipynb  
2.数据增强方法实现 参考augmentation/combination.py, augmentation/role_change.py, augmentation/word_mask.py  
3.数据格式校验 参考config/utils.py

### 待补充部分
数据增强的实验结果

### 参考
[自然语言处理中数据增强（Data Augmentation）技术最全盘点](https://zhuanlan.zhihu.com/p/150600950?from_voters_page=true) 
