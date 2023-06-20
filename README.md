# Cat and Dog Voice Classification
 Objective is classifying the voice with data-based learning. 
Cat and dog voices have different characteristics. Using the Power Spectral Density (PSD), these differences are measured and voices are classed end of the testing section.

Training section has two subsection such as cat training part and dog training part.
In the training part, sample rates and amplitudes are calculated with the librosa library. Then, using the data that collected from sample rates and amplitudes, PSD of the voice is calculated for each audio file. 

