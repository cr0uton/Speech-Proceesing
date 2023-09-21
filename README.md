# ASSIGNMENTS FOR SPEECH PROCESSING

### 1) Assignment 1

   i) Generate an audio file from text mentioning words such as, Sesquipedalian, Perspicacity, Ostentation, Muliebrity, Hippopotomonstrosesquipedaliophobia, Floccinaucinihilipilification, Scripturient.
   
   ii) Analyze that audio using librosa waveplot and spectrogram.
   
   iii) Comment on the output
   
   iv) Record your voice, speak in English and Hindi both, use Speech Recognizer to recognize the recorded audio, comment on the output text
   
### 2) Assignment 2
   i) Select 3 or 4 audio files of happy and sad, generate following plots and explain the inferences in 1-2 lines.

         a. Waveform
         b. Spectrogram on log
         c. Zero Crossing rates
         d. Spectral Centroids
         e. Spectral Bandwidth
         f. MFCC
         
   ii) Extract the MFCC features with 40 components from those 500 audios and build simple logistic regression. Comment on the model output performance. (Try to adjust MFC components)

   iii) Extract the mel spectrogram features with 128 mel bands from those 500 audios and build simple logistic regression. Comment on the model output performance.

   iv)  Compare model results of MFCC and Mel Spectrogram

### 1) Assignment 3
   i) Problem Statement: To build and design CNN model for identification of Dystarthia Disease 

   ii) Read data.csv in pandas
   iii) For any 1 random sample of dysarthric male, dysarthric female, non-dysarthric male, and non-dysarthric female, visualize.
   
         a. Waveplot
         b. Spectrogram
         c. Zero Crossing rate
         d. Spectral Centroid and rolloff,
         e. MFCC
         f. Mel Spectrogram
         
   iv) Comment on the output.
   
   v) Define a function to create 256 MFCC features for any given audio file.
   
   vi) Split the data into training and validation by a ratio of 90:10.
   
   vii) Build the CNN model with padding on a training set.
   
   viii) Evaluate the validation set.
   
   ix) Calculate and comment on ROC AUC score, recall score and confusion matrix
