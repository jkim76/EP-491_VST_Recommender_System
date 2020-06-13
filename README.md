# EP-491_VST_Recommender_System
VST_Recommender_system was developed in Python3.

#Developer\
This Project is developed by "Jungwoo Kim".\
Jungwoo Kim is Alumni from Berklee College of Music.\
\
\
Built and Tested with:\
Jupyter Notebook and Visual studio code\
\
\
Used Libraries.\
Numpy, Pandas, Librosa, Sci-kit Learn\


#Purpose\
The main purpose of this project is to minimized time for searching for sound preset in music production process.\
Most of musicians spend time searching for similar sound preset and instrument that they like to used in their production.\
\
\
\
\
#Project Description\
First, all the audio was recorded via 'Logic' and editted in 'Protools' then manually extracted ideal pitches from VST synthesizer(Serum).\
\
\
Second, by extracting audio feature from each ideal audio samples from 'Serum'.\
I used "Librosa"  to extract different sound features(MFCCs, Spectral Centroid, Spectral Bandwidth, Spectral Contrast, Spectral Rolloff, Spectral Flatness).\
\
\
Third, then I made simple classification problem with audio features and comparing them with default 'Serum' instrument types which is called sound qualities.\
\
\
In the future I'll be adding features of comparing new audio files and its features with trained audio features and recommend similar audio feature from trained data. This will be the product of Content_based filtering recommender system.\
\
\
\
\
#Problems\
First, problem is I don't have enough audio samples to compare. I used only 120 audio samples from Serum.\
\
\
Second, the instrument type of Synthesizer is very wide and different. \
Therefore it is really difficult to define instruments types.\
For example, if I would choose 'Bass' Instrument, there would be 'deep house bass', 'reese bass', ' plucky bass' and so on.\
\
\
Third, the overall accuracy is very low because of the labeling of instrument type is very limited and audio feature is very different from each samples.\
\
\
\
\
#Future improvement\
Therefore, I need to improver accuracy by getting different types of sound qualities and instrument type from different producer and name them properly for machine learning in music field.\



