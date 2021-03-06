# AV-Gaze: A Study on the Effectiveness of Audio Guided Visual Attention Estimation for Non-Profilic Faces

In challenging real-life conditions such as extreme head-pose, occlusions, and low-resolution images where the visual information fails to estimate visual attention/gaze direction, audio signals could provide important and complementary information. In this paper, we explore if audio-guided coarse head-pose can further enhance visual attention estimation performance for non-prolific faces. Since it is difficult to annotate audio signals for estimating the head-pose of the speaker, we use off-the-shelf state-of-the-art models to facilitate cross-modal weak-supervision. During the training phase, the framework learns complementary information from synchronized audio-visual modality. Our model can utilize any of the available modalities i.e. audio, visual or audio-visual for task-specific inference. It is interesting to note that, when AV-Gaze is tested on benchmark datasets with these specific modalities, it achieves competitive results on multiple datasets, while being highly adaptive towards challenging scenarios.

![Scale](/figs/teaser_avgaze.png) 


## Dataset
Please download the data using the link: [Gaze360](https://github.com/erkil1452/gaze360/tree/master/dataset), 

## Pipeline 
![pipeline](/figs/AVGaze_pipeline.png) 

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
This repository makes liberal use of data repositarites from [Gaze360](https://github.com/erkil1452/gaze360).
