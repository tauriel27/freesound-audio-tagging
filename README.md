# [freesound-audio-tagging](https://www.kaggle.com/c/freesound-audio-tagging)
The last month didn't go on with the competition and there was a lot of work to be done :)~
## LB
- public 0.962(14th)
- private 0.939(18th)
## notebooks 
- data-generation
- submission-generation&blending
- NN
## input feature
- 1D raw wave
- 2D MFCC
- 2D log spectrogram
- 2D log mel spectrogram
## technique
- remove silence `librosa.effects.trim`(TODO)
- [mixup](https://arxiv.org/abs/1710.09412)
- [random erasing](https://arxiv.org/abs/1708.04896)
- statistical features(TODO)
- [fusion](https://www.cs.tut.fi/sgn/arg/dcase2017/documents/challenge_technical_reports/DCASE2017_Gong_189.pdf)(TODO)
## 4th solution
[NUDT](https://github.com/Cocoxili/DCASE2018Task2)
## 8th solution
[SainathAdapa](https://www.kaggle.com/c/freesound-audio-tagging/discussion/64262)
