# tasnetmi-samples

Some samples of simulations described in ''Nonlinear Residual Echo Suppression Based on Multi-stream Conv-TasNet''

simulations\
├─snr30dBser-14.2dB\
│&ensp;├─music\
│&ensp;│&ensp; 000000_clean.wav &emsp; # the near-end signal\
│&ensp;│&ensp; 000000_noisy.wav &emsp; # the residual signal of LAEC\
│&ensp;│&ensp; 000000_refer.wav &emsp; # the far-end signal\
│&ensp;│&ensp; 000000_$MODEL$.wav &emsp; # the estimated near-end signal of DNN model named $MODEL$\
│&ensp;│&ensp; ...\
│&ensp;│      \
│&ensp;└─speech\
│&emsp;&emsp;some samples ...\
│           \
└─snr30dBser-18.2dB\
 &emsp; ├─music\
 &emsp; │&ensp; some samples ...\
 &emsp; │      \
 &emsp; └─speech\
 &emsp;&emsp;&ensp; some samples ...

