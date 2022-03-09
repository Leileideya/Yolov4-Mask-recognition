# Yolov4-Mask-recognition
使用 Yolov4 进行身份识别和跌倒检测

一、部署步骤

1.创建虚拟环境

conda create -n *** python=3.7

1.进入目录内

cd Face-Mask-Detection-master

2.安装依赖包

pip install -r requests.txt

3.运行app.py

python3 app.py

# 代码结构
口罩检测：  
 Face-Mask-Dectection-master  
│   ├── app.py		启动文件  
│   ├── eval.ipynb  
│   ├── img_out  
│   ├── make_annotations.ipynb  
│   ├── mAP  
│   ├── model_data  
│   ├── nets		主干特征提取网络  
│   ├── picture  
│   ├── predict.ipynb  
│   ├── predict.py	预测图片	  
│   ├── predict_video.py		预测视频  
│   ├── __pycache__  
│   ├── requirements.txt  
│   ├── static		存放前端相关文件  
│   ├── templates  
│   ├── train.ipynb  
│   ├── utils		先验框与解码  
│   ├── video  
│   ├── video_out  
│   └── yolo.py		特征提取并获取预测结果  

跌倒检测：  
  Fall-Dectection  
│   ├── app.py     启动文件  
│   ├── model	  存放模型  
│   ├── output	   输出  
│   └── testfile     存放测试图片 视频  

# 数据集
跌倒检测数据集链接：https://pan.baidu.com/s/1g-1je2p6iFIC_H1WWKI5HA 
提取码：3243

口罩检测数据集链接：https://pan.baidu.com/s/1MsrlXHKEoo75tfBGSHN8WA 
提取码：3243 
