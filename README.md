# Cat and Dog Voice Classification
The objective is to classify the voice with data-based learning. 

Cat and dog voices have different characteristics. Using the Power Spectral Density (PSD), these differences are measured and voices are classed end of the testing section.

Training section has two subsections such as cat training part and dog training part.
In the training part, sample rates and amplitudes are calculated with the librosa library. Then, using the data that collected from sample rates and amplitudes, PSD of the voice is calculated for each audio file. 

Testing section has two subsections same as the training part. These parts are cat testing part and dog testing part. 
In the testing part, every audio files features are calculated same as the training part. When the PSD is calculated, the audio is ready to be classed. Firstly, differences between testing data and training data have to be calculated. If the differences between cat training data and testing data is close, this audio is classed as cat voice. Otherwise, if the differences between dog training data and testing data is close, this audio is classed as dog voice. 
