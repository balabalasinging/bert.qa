# bert.qa
###### 配置环境:tensorflow1.14.0 keras2.3.1 bert4keras0.8.8 numpy1.16.0
[运行过程中报错而需要修改tensorflow包的内容，参考链接](https://www.jianshu.com/p/1cd9fe04f5ae)
    该项目是基于天池中医文献数据集的阅读理解（QA）项目，运用了bert模型。
    训练代码：code->train.py
    工具代码：utils.py
    数据集：train.json
###### 需要注意的问题：
    需要下载bert模型保存目录:【
    config_path = 'D:/cs224n_2019/chinese_L-12_H-768_A-12/bert_config.json'
    checkpoint_path = 'D:/cs224n_2019/chinese_L-12_H-768_A-12/bert_model.ckpt'
    dict_path = 'D:/cs224n_2019/chinese_L-12_H-768_A-12/vocab.txt'】
    根据保存路径不同，修改以上的path。
###### 初次训练的结果：
![](https://raw.githubusercontent.com/balabalasinging/bert.qa/master/img.png)
    
        
    
