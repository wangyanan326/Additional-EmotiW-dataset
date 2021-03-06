# Additional EmotiW dataset
Additional datasets for the group-based cohesion and emotion understanding tasks. It contains situation description text for static and dynamic visual data.
## Group-based Cohesion Prediction (EmotiW2019)
Linguistic contextual information contains lots of meaningful representation for analyzing group cohesion levels. We manually add japanese text to describe the image of GAF Cohesion dataset from human interaction viewpoint.　<br><br>
As shown in the following figure, There are some samples from GAF 3.0 validation dataset. The description is annotated in Japanese language and added to the training and validation dataset. A high score indicates strong cohesion among people shown in the image. 
<div align="center"><img src="./GAF-sample.jpg" width="640px"></div>

We also provide english text which is converted from japanese text using Goolge translation API. Besides, we extract BERT work embedding features stored in the H5 file so that you can adapt your work easily. Due to the large size of the BERT feature, we send the download link to anyone who needs it.
* **train-bert-jp.h5/valid-bert-jp.h5:** word embedding is extracted using [the pre-trained BERT model provided by kyoto university](http://nlp.ist.i.kyoto-u.ac.jp/index.php?BERT%E6%97%A5%E6%9C%AC%E8%AA%9EPretrained%E3%83%A2%E3%83%87%E3%83%AB).
* **train-bert-en.h5/valid-bert-en.h5:** word embedding is extracted using [BERT pre-trained model provided by Google](https://github.com/google-research/bert).

### Citations
We only release the additional description text data, if you want to utilize our description text with GAF 3.0, you need to connect [EmotiW officer](https://sites.google.com/view/emotiw2019/organizers?authuser=0) to get GAF 3.0 dataset.  And don't forget to refer the following papers.

```BibTeX
@INPROCEEDINGS{gaf,
  author={S. {Ghosh} and A. {Dhall} and N. {Sebe} and T. {Gedeon}},
  booktitle={2019 International Joint Conference on Neural Networks (IJCNN)}, 
  title={Predicting Group Cohesiveness in Images}, 
  year={2019},
  volume={},
  number={},
  pages={1-8},}
```

```BibTeX
@inproceedings{ldnn,
author = {Wang, Yanan and Wu, Jianming and Huang, Jinfa and Hattori, Gen and Takishima, Yasuhiro and Wada, Shinya and Kimura, Rui and Chen, Jie and Kurihara, Satoshi},
title = {LDNN: Linguistic Knowledge Injectable Deep Neural Network for Group Cohesiveness Understanding},
year = {2020},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
series = {ICMI ’20}
}
```

## Audio-video Group Emotion Recognition (EmotiW2020)
We mannualy describe the video of the VGAF dataset in Japanese language. VGAF is a video dataset and used for predicting group emotion in the video.  
We only provide additional description data at here, and you can get VGAF dataset by connecting [EmotiW officer](https://sites.google.com/view/emotiw2020/organizers?authuser=0). 

The BERT word embedding features of descriptions also can be downloaded if you comment that you need it. The following H5 files you could get. The word embedding is extracted using [the pre-trained BERT model provided by kyoto university](http://nlp.ist.i.kyoto-u.ac.jp/index.php?BERT%E6%97%A5%E6%9C%AC%E8%AA%9EPretrained%E3%83%A2%E3%83%87%E3%83%AB).
* **train-bert-jp-d768-VGAF.h5** 
* **valid-bert-jp-d768-VGAF.h5** 

### Citations
If you use VGAF in your work, please don't forget refer these papers in your work.

```BibTeX
@inproceedings{sharma2019automatic,
  title={Automatic Group Level Affect and Cohesion Prediction in Videos},
  author={Sharma, Garima and Ghosh, Shreya and Dhall, Abhinav},
  booktitle={2019 8th International Conference on Affective Computing and Intelligent Interaction Workshops and Demos (ACIIW)},
  pages={161--167},
  year={2019},
  organization={IEEE}
}
```
```BibTeX
@inproceedings{wang@injection,
  title={Implicit Knowledge Injectable Cross Attention Audiovisual Model for Group Emotion Recognition},
  author={Yanan Wang, Jianming Wu, Panikos Heracleous, Shinya Wada, Rui Kimura, and Satoshi Kurihara},
  year = {2020},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  series = {ICMI ’20}
}
```

## Contact
Please contact Abhinav Dhall(abhinav.dhall@monash.edu) and Garima Sharma(garima.sharma1@monash.edu) for questions about GAF 3.0 and VGAF dataset including the raw images and videos. And contact Yanan Wang(wa-yanan@kddi-research.jp) for quesions about the additional linguistic data of them.

# License
**The additional linguistic data can only be used for academic/non-commercial purpose.**
