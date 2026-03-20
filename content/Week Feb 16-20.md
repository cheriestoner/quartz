## Literature research
- "Crossmodal correspondences" is broader than synaesthesia: "The term synaesthetic congruency usually refers to correspondences between putatively nonredundant stimulus attributes or dimensions that happen to be shared by many people."
- crossmodal correspondences are verified in speeded classification tasks with simultaneous multimodal stimuli
	- fail to address individual differences in polarities/directions
- Time-frequency representations compared, do they work for sensory substitution interface, and which is the best?
	- Spectrogram
		- FFT
		- Wavelet
		- gammatone
		- Mel
	- MPS


## Experiment design
- Drafted the experiment protocol for the first small study about vocal production type discrimination based on spectrograms

|**Method**|**Frequency scale**|**Time resolution**|**Perceptual alignment**|**Invertibility**|
|---|---|---|---|---|
|FFT/STFT|Linear or log|Fixed (window trade-off)|Low|Fully invertible|
|Gammatone|Cochlear-like|Fixed per filter|Medium–high|Approximate|
|Wavelet|Multi-resolution|Adaptive|High for transients|Approximate|
