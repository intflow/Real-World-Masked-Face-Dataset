# 한글 번역 README.md

## Real-World Masked Face Dataset (RMFD)
최근 세계적으로 신종 코로나 바이러스가 기승을 부리고 있는 가운데 우한에서는 거의 사람들이 마스크를 착용하고 있고, 따라서 마스크 착용한 사람의 데이터 샘플 수집이 가능하다. 따라서 샘플을 수집해 세계 최대 마스크 안면 데이터 집합을 만들고 이를 사회에 개방해 현재 및 향후 예상되는 공공 안전 사태와 같은 스마트 컨트롤을 위한 데이터 자원을 축적했다. 마스크 안면 데이터에 기반해 마스크 검사와 인식 알고리즘을 설계하여 건물의 출입통제, 역 및 공항 등에서의 보행자 마스크 착용 여부에 대한 판단이 가능할 것으로 생각된다

데이터 제공 기관: 우한대학교 국가멀티미디어소프트웨어공정기술연구센터
연락처: 黄宝金, huangbaojin@whu.edu.cn

ps. 데이터 셋을 더 확장하기 위해 개인적으로 수집한 마스크 착용 사진을 e-메일로 보내주시면 감사하겠습니다.

## 데이터셋 다운로드
일부 오리지날 샘플은 본 github 스테이션에 업로드 되었으며, RMFD_part_1은 직접 다운로드 받아서 사용할 수 있으며, RMFD_part_2 (4개의 압축파일)와 RMFD_part_3 (3개의 압축파일)는 압축파일 전체를 다운로드한 후 압축해제가 필요합니다. 다운로드 주소는 아래와 같습니다.
다운로드 링크: https://pan.baidu.com/s/1Vly3K-0qjlB6M2lenTZ8PA 비밀번호: xhze
또는 다운로드 링크: https://drive.google.com/open?id=1kZAIiv34Iav9Vt8BB101FXo4KoEClpx9

얼굴 마스크 인식(또는 검사) 데이터 셋과 달리 마스크 인식 데이터셋은 마스크와 마스크를 착용하지 않은 사람의 얼굴 이미지를 모두 포함해야 하기 때문에 두 가지 마스크 인식 샘플 집합을 만들었다.

1. 실제 마스크 안면 인식데이터셋: 인터넷상에서 샘플을 채취해 정리, 클리닝, 레이블링 한 결과, 525명이 착용한 마스크 5000장을 포함해 9만 명의 얼굴 데이터를 얻을 수 있었다.
다운로드 링크: https://pan.baidu.com/s/1XvGepj84SCA9rlVb9rGhEQ 비밀번호：j3aq
또는 다운로드 링크: https://drive.google.com/open?id=1UlOk6EtiaXTHylRUx2mySgvJX9ycoeBp

2. Simulated 마스크 안면 인식 데이터셋: 데이터가 공개된 사람의 얼굴에 마스크를 씌워 1만명, 50만 장의 얼굴을 얻은 아날로그 마스크 얼굴 데이터 집합이다.
WebFace 아날로그 마스크 안면 데이터셋
다운로드 링크: https://pan.baidu.com/s/1Qi_8D_kH2QCm761elZs5YA 비밀번호: 77m8
또는 다운로드 링크: https://drive.google.com/open?id=1q0ibaoFVEmXrjlk3-Oyx2oYR8HpVy6jc

3. LFW Simulated 마스크 안면 데이터셋
다운로드 링크：https://pan.baidu.com/s/1Ge0KcYgu6oVAbLlDHCKwRg 비밀번호: o126
또는 다운로드 링크: https://drive.google.com/open?id=1soLIUkGruSKMzg5z5_OYYqUVoca4E_lI

## 마스크 안면 인식
구축된 데이터 집합에 기초하여 얼굴-눈썹 multi-granularity mask face recognition 모델을 설계 및 훈련하였으며, 데이터 집합의 식별정도가 95%에 달함.
다운로드 링크: https://pan.baidu.com/s/1P0PiWFNT1z_TcCj8vo43ow 비밀번호: acwe 
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wnx.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wuhao.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/hzb.gif)

## 관련 논문
https://arxiv.org/abs/2003.09093

## 데이터셋 샘플 예시
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0003.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0001.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0002.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/0.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/1.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/2.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/3.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/4.jpg)

---

# 口罩遮挡人脸数据集（Real-World Masked Face Dataset，RMFD）

近期全球新型冠状病毒肆虐，疫情严重地区（如武汉）几乎人人戴口罩，具有海量样本基数。收集样本建立全球最大口罩人脸数据集，并向社会开放，为当前及今后可能的类似公共安全事件智能管控积累数据资源。基于口罩人脸数据，设计相应口罩遮挡人脸检测和识别算法，帮助社区封闭时的人员进出管控，车站、机场的人脸识别闸机以及人脸门禁考勤设备的升级，适应行人口罩蒙面遮挡的应用环境。

发起单位：武汉大学国家多媒体软件工程技术研究中心

联系人：黄宝金，联系邮箱：huangbaojin@whu.edu.cn

为了进一步扩充数据集，欢迎大家将个人收集到的戴口罩图片，通过邮件的方式发送到 huangbaojin@whu.edu.cn，我们会对收到的图片统一处理。

## 数据集下载

部分原始样本已上传本github站点，RMFD_part_1可直接下载使用，RMFD_part_2 (4个压缩文件) 和RMFD_part_3 (3个压缩文件) 需要下载全部压缩文件后，再进行解压。也可以从下方的地址下载：

链接: https://pan.baidu.com/s/1Vly3K-0qjlB6M2lenTZ8PA 提取码: xhze 

或者 https://drive.google.com/open?id=1kZAIiv34Iav9Vt8BB101FXo4KoEClpx9

已标注数据集说明如下：（区别于github中raw samples） 不同于人脸口罩识别（或检测）数据集，口罩人脸识别样本集须得包含同一人的多张戴口罩与未戴口罩的人脸图像，为此，我们建立了两种口罩人脸识别样本集。

(1) 真实口罩人脸识别数据集：从网络爬取样本，经过整理、清洗和标注后，含525人的5千张口罩人脸、9万正常人脸。 

下载地址： https://pan.baidu.com/s/1XvGepj84SCA9rlVb9rGhEQ 密码：j3aq

或者 https://drive.google.com/open?id=1UlOk6EtiaXTHylRUx2mySgvJX9ycoeBp


(2) 模拟口罩人脸识别数据集： 给公开数据集中的人脸戴上口罩，得到1万人、50万张人脸的模拟口罩人脸数据集。 

WebFace模拟口罩人脸数据集： 

下载地址： https://pan.baidu.com/s/1Qi_8D_kH2QCm761elZs5YA 密码: 77m8 

或者 https://drive.google.com/open?id=1q0ibaoFVEmXrjlk3-Oyx2oYR8HpVy6jc

LFW模拟口罩人脸数据集: 

下载地址：https://pan.baidu.com/s/1Ge0KcYgu6oVAbLlDHCKwRg 密码: o126

或者 https://drive.google.com/open?id=1soLIUkGruSKMzg5z5_OYYqUVoca4E_lI

## 口罩人脸识别

基于建立的数据集，设计和训练了面部-眉眼多粒度口罩人脸识别模型，数据集上的识别精度达到95%，部分动态视频演示见：

链接: https://pan.baidu.com/s/1P0PiWFNT1z_TcCj8vo43ow 提取码: acwe 

![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wnx.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wuhao.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/hzb.gif)



## 相关工作

https://arxiv.org/abs/2003.09093

## 原始样本示例：

![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0003.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0001.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0002.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/0.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/1.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/2.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/3.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/4.jpg)

#
# Real-World Masked Face Dataset（RMFD）

Because of the recent epidemic of COVID-19 virus around the world, people across the country wear masks and there appear a large number of masked face samples. We thus created the world's largest masked face dataset to accumulate data resources for possible intelligent management and control of similar public safety events in the future. Based on masked face dataset, corresponding masked face detection and recognition algorithms are designed to help people in and out of the community when the community is closed. In addition, the upgrade of face recognition gates, facial attendance machines, and facial security checks at train stations is adapted to the application environment of pedestrian wearing masks.

Sponsor: National Engineering Research Center for Multimedia Software (NERCMS), School of Computer Science, Wuhan University

Contact: Baojin Huang, Email: huangbaojin@whu.edu.cn

In order to further expand this dataset, everyone is welcome to send personally collected pictures of masks to huangbaojin@whu.edu.cn by email, and we will process the received pictures uniformly.

## Download Datasets

Part of the original samples has been uploaded to this github website. RFMD_part_1 can be downloaded directly. RFMD_part_2 (4 compressed files) and RFMD_part_3 (3 compressed files) need to download all compressed files before decompressing them.You can also download these datasets from the link below.

Download link: https://pan.baidu.com/s/1Vly3K-0qjlB6M2lenTZ8PA Password: xhze 

or https://drive.google.com/open?id=1kZAIiv34Iav9Vt8BB101FXo4KoEClpx9

More labeled face samples are illustrated as follows: (different from raw samples in github) Different from the facial mask recognition (or detection) dataset, the masked face recognition dataset must include multiple masked and unmasked face images of the same subject. To this end, we have established two kinds of masked face recognition datasets. 

(1)	Real-world masked face recognition dataset: We crawled the samples from the website. After cleaning and labeling, it contains 5,000 masked faces of 525 people and 90,000 normal faces. 

Download link: https://pan.baidu.com/s/1XvGepj84SCA9rlVb9rGhEQ  Password: j3aq

or https://drive.google.com/open?id=1UlOk6EtiaXTHylRUx2mySgvJX9ycoeBp

(2)	Simulated masked face recognition datasets: We put on the masks on the faces in the public face datasets, and obtained the simulated masked face dataset of 500,000 faces of 10,000 subjects.

WebFace simulated masked face dataset:
https://pan.baidu.com/s/1Qi_8D_kH2QCm761elZs5YA Password: 77m8

or https://drive.google.com/open?id=1q0ibaoFVEmXrjlk3-Oyx2oYR8HpVy6jc

LFW simulated masked face dataset:
https://pan.baidu.com/s/1Ge0KcYgu6oVAbLlDHCKwRg Password: o126

or https://drive.google.com/open?id=1soLIUkGruSKMzg5z5_OYYqUVoca4E_lI

## Masked Face Recognition

Based on the constructed datasets, we designed and trained a face-eye-based multi-granularity masked face recognition model. The face identification accuracy on the dataset is over 95%, and some real-time video demos are as follows:

Download link: https://pan.baidu.com/s/1P0PiWFNT1z_TcCj8vo43ow Password: acwe 

![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wnx.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wuhao.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/hzb.gif)


## Related Work

https://arxiv.org/abs/2003.09093
 
## Examples of Raw Samples

![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0003.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0001.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0002.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/0.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/1.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/2.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/3.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/4.jpg)
