# Signals-Systems-CEP-matlab
**Q.1:** For this problem, you have to put the .m file and an audio signal in the same folder so that the script 
can load it after every edit. Otherwise you have to specify the address of your local disk where sound file 
resides, into the MATLAB script. 

i. Download the script provided sample.m, and use it to record your own voice and save this file 
name_rollnumber.wav. Read, store, and play different sound samples of the audio file, scale it, 
increase the volume of track, adjust the sampling rate to speed up or slow down the track, add text 
to the file, visualize the sound, and play the track backwards. Provide .mlx file for each task 
specified. ‘.mlx’ file is generated via MATLAB LiveScript. [5 Marks]

ii. Downsample your file name_rollnumber.wav, without using anti-aliasing filter and then use antialiasing filter first and then down-sample your voice. Enlist your observations about the output files 
and anti-aliasing filters in terms of Nyquist. Apply FFT to both output files and discuss frequency 
spectrum results. [15 Marks]

iii. Now add some noise to your audio signal, and design a filter to remove any unwanted noise or 
jitter from your updated voice signal. Explain performance criterion of filter being used and all the 
steps involved to do the process using a block diagram. Submit the simulation, ‘.mlx’ files as well as 
‘.wav’ files (noisy & clean after noise removal). [15 Marks]


**Q.2: Compose a music:** Download two different ten seconds .wav files of two musical instruments i.e piano 
and guitar. Load them in matlab and compose a new music symphony out them. You can start by specifying 
a sampling rate, a table of frequencies (220-440Hz) corresponding to the musical Notes of Piano and guitar
where each Note can be represented as sinusoids followed by a pause, to discriminate between different 
Notes of the same pitch. Submit .m file of your code and all input and output .wav files. [25 Marks]
