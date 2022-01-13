# multistage-ser
## Abstract

Due to its ability to accurately predict emotional state using multimodal features, audiovisual emotion recognition has recently gained more interest from researchers. This paper proposes two methods to predict emotional attributes from audio and visual data using a multitask learning and a fusion strategy. First, multitask learning is employed by adjusting three parameters for each attribute to improve the recognition rate. Second, a multistage fusion is proposed to combine results from various modalities’ final prediction. Our approach used multitask learning, employed at unimodal and early fusion methods, shows improvement over single-task learning with an average CCC score of 0.431 compared to 0.297. A multistage method, employed at the late fusion approach, significantly improved the agreement score between true and predicted values on the development set of data (from [0.537, 0.565, 0.083] to [0.68, 0.656, 0.443]) for arousal, valence, and liking.

## Usage
~~~
python3 fuse_result_3.py
~~~

## Citation
B. T. Atmaja and M. Akagi, “Multitask Learning and Multistage Fusion for Dimensional Audiovisual Emotion Recognition,” in ICASSP, IEEE International Conference on Acoustics, Speech and Signal Processing - Proceedings, May 2020, vol. 2020-May, pp. 4482–4486, doi: 10.1109/ICASSP40776.2020.9052916.
