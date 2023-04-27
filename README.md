# Audio_analysis

Predicting_Emotions_through_audio_analysis
I'm starting a project to create an emotion classifier for audio data, and found the TESS dataset for it. This dataset stands out since it only includes female speakers and has incredibly good audio. This dataset is the perfect training dataset for my emotion classifier, enabling more generalization and reducing overfitting.

The TESS dataset consists of 2800 audio files in total, with recordings made for each of the seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral) and a set of 200 target words spoken in the carrier phrase "Say the word _" by two actresses, ages 26 and 64. All 200 target word audio files are included, and the audio files are organized in a folder system that differentiates each female performer and her associated emotions. Because the audio files are saved in the WAV format, a variety of audio processing ato waveform and sampling srpplications are compatible with them.

What to learn in this project.

Converting Audio -> waveform and sampling rate

normalized audio -> Np.array samples
