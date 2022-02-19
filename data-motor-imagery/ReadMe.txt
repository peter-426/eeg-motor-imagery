EEG data of simple and compound limb motor imagery.

There are ten files from ten subjects stored in three zip files: data1, data2 and data3.
Each file contains EEG 'data' (Channel*Time*Trial) and labels.
Data is from 64 channels. 560 trials, i.e. 560 =  80 x 7 classes each.
So, eeg.shape == (64,1600,560). The data were band-pass filtered between 0.1 and 50Hz. 
Each EEG waveform is 8s long (1600 time points), 
sampling rate is 200Hz. There are 560 labels,  1-7 indicate 
left hand, right hand, both hands, feet, left hand combined with right foot, right hand 
combined with left foot and resting state respectively.

Data set : https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/27306

 
If you have any questions, please contact the data set author at yiweibo1987@163.com