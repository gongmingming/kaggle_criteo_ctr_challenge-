# kaggle_criteo_ctr_challenge-
This is a kaggle challenge project called Display Advertising Challenge by CriteoLabs at 2014.
这是2014年由CriteoLabs在kaggle上发起的广告点击率预估挑战项目。
使用TensorFlow1.0和Python 3.5开发。

__Author__ chengstone

__e-Mail__ 69558140@163.com

代码详解请参见jupyter notebook和↓↓↓

博客：http://blog.csdn.net/chengcheng1394/

知乎专栏：https://zhuanlan.zhihu.com/DeepLearningSelfDriving

欢迎转发扩散 ^_^

本文使用GBDT、FM、FFM和神经网络构建了点击率预估模型。

## 网络模型
![image](https://raw.githubusercontent.com/chengstone/kaggle_criteo_ctr_challenge-/master/model.png)

## LogLoss曲线
![image](https://raw.githubusercontent.com/chengstone/kaggle_criteo_ctr_challenge-/master/tensorboard.png)

## 验证集上的训练信息
 - 平均准确率
 - 平均损失
 - 平均Auc
 - 预测的平均点击率
 - 精确率、召回率、F1 Score等信息
    Test Mean Acc : 0.7814300060272217
    Test Mean Loss : 0.46838584542274475
    Mean Auc : 0.7792937214782675
    Mean prediction : 0.2552148997783661
                 precision    recall  f1-score   support

            0.0       0.81      0.93      0.86     74426
            1.0       0.63      0.34      0.45     25574

    avg / total       0.76      0.78      0.76    100000

更多内容请参考代码，Enjoy！