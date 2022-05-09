# ASR-Speech-to-text-Mid-term-Project-
## Development of template matching technique for speech to text conversion 

## DECLARATION
We declare that this mini project, submitted for the evaluation of course work of Mini Project
to Manipal School of Information Sciences, is an existing idea/concept/code available at
(https://jonathan-hui.medium.com/speech-recognition-acoustic-lexicon-language-modelaacac0462639,
https://medium.com/@kangeugine/hidden-markov-model-7681c22f5b9)),
conducted under the supervision of my guide Prof. Raghudathesh G P and panel members,
Prof. SamarendranathBhattacharya, Dr. Harishchandra Hebbar References, help and
material obtained from other sources have been duly acknowledged.

# ABSTRACT
The fundamental of speech dates back in time wherein humans began to communicate with
one other. Over the time it was realized that it is an effective medium of commutation. Later
on, it acquired various forms and thus different languages came into existence. On close
analysis it has been found that there are over hundreds of different languages; English being
the most widely used.
Accordingly, most the formal talks are in English. Most of the communication devices these
days like security devices, home appliances, mobile phones, ATM machines, computers and
hotels use speech processing. Our project focuses on establishing an interface between these
two. The human computer interface has been developed in order to communicate and interact
with ones who are suffering from different types of disabilities. Speech-to-Text Conversion
(STT) system is advantageous for deaf and dumb people. It is also used in our day to day
lives. The main aim of our system is to convert input speech signals into text as output. This
project extract features of the speech signal by Mel-Frequency Cepstral Coefficients(MFCC)
for multiple isolated words. Gaussian Mixture Model (GMM) and Hidden Markov Model
(HMM) are used to train the audio files to get the spoken word recognized.
Keywords
Mel-Frequency Cepstral Coefficients(MFCC), Gaussian Mixture Model (GMM), Hidden
Markov Model (HMM)

## Contents
* 1 Objective 
* 1.1 Introduction 
* 1.2 Problem definition 
* 1.3 Automatic Speech Recognition 
* 2 Project design status 
* 2.1 Architecture 
* 2.2 Implementation 
* 2.2.1 Acquisition of speech recordings from user 
* 2.2.2 Segmentation of speech recordings at phoneme level 
* i) Feature Extraction 
* ii) Pattern Classification 
* iii) Parametric vs Non-Parametric Classification 
* iv) HMM 
* 2.3 Template matching of segmented phone for each recording 
* 2.4 Decision Rule 
* 2.5 Confidence Measure 
* 2.6 Displaying of uttered/spoken word 
*  Test environment creation 
*  Result obtained 
*   Challenges faced 
*   Lessons learnt 
*   References 

![image](https://user-images.githubusercontent.com/70902291/167429247-9e5d91f0-8d4e-4909-b03e-8dc38f6a74aa.png)


![image](https://user-images.githubusercontent.com/70902291/167429399-0f15e9ba-aafb-43ce-be8f-0f2e93a54183.png)

![image](https://user-images.githubusercontent.com/70902291/167429564-0b0043d9-de77-4c61-b222-910afca38da2.png)

![image](https://user-images.githubusercontent.com/70902291/167429768-0f725436-0402-436b-83cc-03bc2d4c6753.png)


## Kannada Dataset

![image](https://user-images.githubusercontent.com/70902291/167429838-1008c915-003d-474d-a681-4752d25319e1.png)

![image](https://user-images.githubusercontent.com/70902291/167429912-ef796c33-aacb-4f0f-a2dc-aea5abefea1d.png)


# References
Dataset:
https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data

# Program Codes:
https://github.com/UNREALre/SpeechRecognitionHMM_Basics
https://www.kaggle.com/ilyamich/mfcc-implementation-and-tutorial
Reports:
* 1. SPEECH TO TEXT CONVERTER USING GAUSSIAN MIXTURE
MODEL(GMM), Virendra Chauhan 1 , Shobhana Dwivedi 2 , Pooja Karale 3 , Prof.
S.M. Potdar 4
1,2,3 B.E Student
4 Assitant Professor of Electronics and Telecommunication Engineering
1,2,3,4 Sinhgad academy of Engineering, Pune 443001

* 2. Speech Recognition based on Template Matching and Phone Posterior
* Probabilities
* a Cédric Gaudard
* b Guillermo Aradilla
* b Hervé Bourlard
* IDIAP–Com 07-02
* a EPFL student, MSc. internship performed at IDIAP
* b IDIAP Research Institute
* 3. Gaussian Mixture Models
* Douglas Reynolds
MIT Lincoln Laboratory, 244 Wood St., Lexington, MA 02140, USA
# Online references:
1. https://medium.com/@kangeugine/hidden-markov-model-7681c22f5b9
2. https://jonathan-hui.medium.com/speech-recognition-gmm-hmm-8bb5eff8b196
3. https://jonathan-hui.medium.com/speech-recognition-feature-extraction-mfcc-plp-
5455f5a69dd9
4. https://jonathan-hui.medium.com/speech-recognition-acoustic-lexicon-languagemodel-
aacac0462639
Manipal

