# DeepVisual - EEG-based picture reconstruction

<!--(https://www.kentpaulette.com/wp-content/uploads/dream-bear-painting-artist-kent-paulette.jpg)-->
<img src="https://www.kentpaulette.com/wp-content/uploads/dream-bear-painting-artist-kent-paulette.jpg" width="600px" />

## Connect
<a href="https://mattermost.brainhack.org/brainhack/channels/DeepVisual" target="_blank"><img src="http://www.mattermost.org/wp-content/uploads/2016/03/logoHorizontal.png" width=150px /></a>
<a href="https://meet.jit.si/DeepVisual" target="_blank">
<img src="https://jitsi.org/wp-content/uploads/2018/11/jitsi-logo-blue-grey-text.png" width=100px/> </a>


## Goals
Tier 1 goal is to predict seen image category based on EEG time series produced during visual perception of the former.
The ultimate goal is try to reconstruct whole image (i.e., pixel to pixel) from EEG time series.
Here, we are using Deep Learning approach.

## Data 
Data suitable for the first goal is e.g. from Rashkov G. et al. (2019) https://doi.org/10.1101/787101. Dataset is openly accessible at https://data.mendeley.com/datasets/s2dxrv45fr/1. Pitily, the researchers couldn't include whole shown video clips because of copyright issues, only screenshots - so the second goal is only achievable after some data transformation.
The second goal affine dataset should at some point be uploaded by instigators of Brainhack Geneva 2019 project (see Credentials) and be made publically available.
We are welcoming any clues about further suitable dataset - don't hesitate to drop a message on Mattermost channel, or open an issue here!

## Methods
Year 2019 appears to be bursting even with *review* articles on Deep Learning using EEG data. [One of the reviews](https://iopscience.iop.org/article/10.1088/1741-2552/ab0ab5) finds CNN, Deep Belief Networks and Multilayer Perceptrons to be the most often used models for learning on EEG data. If we consider "emotion recognition" task setup to naturally correlate with at least the first task setting (classification of seen image), it is indeed interesting to try Deep Belief Networks on our data.

## Credits
This project was begun during Brainhack Geneva 2019. Credits for the scientific idea go to the Team 10 of instigators of Brainhack Geneva 2019 (Konstantinos S.-T., Timokleia K., Florian L. and Carolina L.). Technical idea and way of implementation is of the owner of this repository, [Stefan Dvoretskii](mailto:stefan.dvorezky@gmail.com).

