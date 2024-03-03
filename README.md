 Binary Classification of Emotions Using Hybrid Model onSpectrogram Images formed on Beta And GammaWaveFrequencyofGAMEEMO-EEG Signal Dataset.
  
  
  
  
  Abstract:Electroencephalography (EEG)-based emotion recognition attempts to detect the affective states of humans directly via spontaneous EEG signals, bypassing the peripheral nervous system. In this project, 
  we explore various transfer learning techniques for EEG-based emotion recognition, and focus on the three research tasks outlined as follows:
 1. Converting EGG signal to Spectrogram Images using stft value of EEG signal Dataset
 2. Classification by using Transfer learning Model trained on these spectrogram images.
 3. Using Hybrid Model which has pretrained Transfer learning model as feature extractor and a binary classifier.


    Objectives:
 The aim of this project is to find the effectiveness of transfer learning models and hybrid models in
 predicting human emotions using images formed by Spectrogram .

Dataset:  In this, dataset GAMEMOO is used to evaluate the Pre trained Transfer learning models. Data processing methods and experiment results are presented.
 This dataset includes computer games-based EEG signals. They are collected from 28 different
 subjects with wearable and portable EEG device called 14 channel Emotiv Epoc+. Subjects played
 emotionally 4 different computer games (boring, calm, horror and funny) for 5 minutes and totally 20
 minutes long EEG data available for each subject. Subjects rated each computer game based on the
 scale of arousal and valence by applying SAM form. We provided both raw and preprocessed EEG data
 with .csv and. mat format in our data repository. Each subject's rating score and SAM form are also
 available. The aim of this dataset is to provide an alternative data for emotion recognition process and
 show the performance of wearable EEG devices against traditional ones. In the main folder
 (GAMEEMO)researches will find 29 different folders (28 for subjects and 1 for gameplay). S01, S02, …
 represents the subjects who participated in the experiment. Gameplay folder shows the gameplay of
 each game. In each subjects folder, researchers will find preprocessed EEG data, raw EEG data csv and
 .mat format. Also SAM ratings are available with .pdf format. Games are represented as G1, G2, G3,
 and G4. G1 refers Game 1, G2 refers G2, and so on.

 
