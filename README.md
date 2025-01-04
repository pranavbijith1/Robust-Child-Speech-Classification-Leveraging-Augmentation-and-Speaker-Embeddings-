This research was conducted by the following:

Pranav Bijith,
Alexander Gardiner, 
Leonard Collomb, 
Sebastian Farrington,
Andrew Liu

The abstract is as follows:

Classifying child speech is challenging due to the limited availability of large, publicly accessible datasets recorded in consistent environments. 
This study aimed to develop a classifier to differentiate child and adult speech using datasets such as LibriSpeech, VoxCeleb, Common Voice, OGI Kids, CMU Kids, and MyST. 
Initial attempts using diarization and embeddings from ECAPA-TDNN, Whisper, and HuBERT led to misclassification due to dataset-specific clustering caused by recording artifacts. 
To address this, data augmentation with impulse responses was applied, improving generalization. A fine-tuned gradient boosting classifier trained on ECAPA-TDNN embeddings achieved 93.5% accuracy. 
Future efforts will explore enhanced augmentation and model tuning for further improvements.

We want to thank Graduate student, Natarajan Balaji Shankar (UCLA), for being our research mentor and guiding us through the research process.  The entirety of the paper can found in this repo along with the colabs used.  

