## IDS-CNN（使用卷积神经网络进行网络入侵检测）
handle2.py为数据预处理代码

main.py为一层全连接层处理kddcup.data_10_percent_corrected_handled2.cvs数据代码  

cnn_mian.py为卷积神经网络处理kddcup.data.corrected_handled2.cvs数据的代码  

以上两个数据集由文件夹中两个.gz文件解压得到  

multi_logs文件夹记录了训练过程中TensorFlow中张量的变化及模型准确率和loss的变化日志（tensorbord）  
