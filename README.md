kaggle-cassava-leaf-disease-exploratory说明

cassava-leaf-disease-cnn：常规模型 得分0.55 只有1次训练
cassava-leaf-disease-EfficientNetB0： 得分0.602 只有1次训练 只能kaggle上运行（from tensorflow.keras.applications import EfficientNetB0 ）在电脑上改为import efficientnet.keras as efn；并且先要安装稳定版（efficientnet必须先安装）pip install -U efficientnet -i https://pypi.tuna.tsinghua.edu.cn/simple（EfficientNetB0权重已经下载至本地文件夹kaggle中）

2020-12-13 增加cassava-leaf-disease-effb7 得分0.843 ；以前的问题可能出在predictions部分（已改进）本例只训练了5个epochs

2020-12-15增加联合模型cassava-leaf-disease-combine.ipyn

2020-12-21EfficientNetB3 得分：0.861 加入了rescale=1./255

