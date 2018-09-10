This repository contains MP3 samples created with the DNN-based controllable TTS system with Methods A, B, and C (refer to [the paper](https://github.com/KurtAhn/SLCV/blob/master/report.pdf)). Briefly, Method A contains only the acoustic model and uses natural speech duration, Method B uses a duration model to predict duration, and Method C uses a style predictor to find an appropriate style offset for input text. 
For each method, three vectors (`(0,0), (-1,1), (1,-1)`) were used to synthesize 185 sentences not seen during training of any of the models.
