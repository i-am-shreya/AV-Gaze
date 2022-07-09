# AV-Gaze: A Study on the Effectiveness of Audio Guided Visual Attention Estimation for Non-Profilic Faces

In challenging real-life conditions such as extreme head-pose, occlusions, and low-resolution images where the visual information fails to estimate visual attention/gaze direction, audio signals could provide important and complementary information. In this paper, we explore if audio-guided coarse head-pose can further enhance visual attention estimation performance for non-prolific faces. Since it is difficult to annotate audio signals for estimating the head-pose of the speaker, we use off-the-shelf state-of-the-art models to facilitate cross-modal weak-supervision. During the training phase, the framework learns complementary information from synchronized audio-visual modality. Our model can utilize any of the available modalities i.e. audio, visual or audio-visual for task-specific inference. It is interesting to note that, when AV-Gaze is tested on benchmark datasets with these specific modalities, it achieves competitive results on multiple datasets, while being highly adaptive towards challenging scenarios.

![Scale](/figs/depression_intensity.png) 


## Dataset
Please download the data using the link: [MDDL](https://github.com/sunlightsgy/MDDL) 

## Pipeline 
![pipeline](/figs/framework_depression.png) 

If you find the paper/code useful for your research, please consider citing our work:
```
@article{ghosh2021avgaze,
  title={AV-Gaze: A Study on the Effectiveness of Audio Guided Visual Attention Estimation for Non-Profilic Faces},
  author={Ghosh, Shreya and Dhall, Abhinav and Hayat, Munawar and Knibbe, Jarrod},
  journal={arXiv preprint arXiv:2207.03048},
  year={2022}
}
```

## Acknowledgements
This repository makes liberal use of data repositarites from 
[MDDL](https://github.com/sunlightsgy/MDDL), [NLTK](https://www.nltk.org/index.html), [text-vad](https://github.com/bagustris/text-vad), [Sentiment-Analysis-ANEW](https://github.com/nisarg64/Sentiment-Analysis-ANEW), [SentimentAnalysis](https://github.com/dwzhou/SentimentAnalysis), [topic-modeling-to-identify-depression-markers](https://github.com/abhilashhn1993/topic-modeling-to-identify-depression-markers).
