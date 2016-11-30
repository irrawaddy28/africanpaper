## Title: Automatic speech recognition using probabilistic transcriptions in Swahili, Amharic, and Dinka

## Authors: Amit Das, Preethi Jytohi, Mark Hasegawa-Johnson

## Status: Published in Interspeech 2016 

## Abstract:
In this study, we develop automatic speech recognition systems for three sub-Saharan African languages
using probabilistic transcriptions collected from crowd workers who neither speak nor have any familiarity
with the African languages. The three African languages in consideration are Swahili, Amharic, and Dinka. There is a language mismatch in this scenario. More specifically, utterances spoken in African languages were transcribed by crowd workers who were mostly native speakers of English. Due to this, such transcriptions are highly prone to label inaccuracies. First, we use a recently introduced technique called mismatched crowdsourcing which processes the raw crowd transcriptions to confusion networks. Next, we  adapt both multilingual hidden Markov models (HMM) and deep neural network (DNN) models using the probabilistic transcriptions of the African languages.  Finally, we report the results using both deterministic and probabilistic phone error rates (PER). Automatic speech recognition systems developed using this recipe are particularly useful for low resource languages where there is limited access to linguistic resources and/or transcribers in the native language.

## Code: 
- git clone -b interspeech16 https://github.com/irrawaddy28/SBS-kaldi.git
