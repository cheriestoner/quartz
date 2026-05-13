Goals:
1. Familiarize with & design the stimulus set (beyond speech dataset)
	- the structure of the dataset
	- quality and characteristics of the audio recordings (some singing has instrumental background)
	- how many for each category, what is missing, what is balanced/unbalanced
2. Learn to use Labvanced
	- Webcam eyetracking reliable? comparable to eyelink; which tasks?
3. Improve the web interface
	- Animation starts from the middle/ 1/3 
	- Scroll from left to right
	- As if the visuals appears from nowhere
	- Color map: Ask Nicolas about the perceptual smooth color map
4. Literature review
---
# 1 Stimuli set analysis
[[Beyond speech stimuli set]]
**Key observations:**
- Categories unbalances (most are nonverbal vocalisations)->stimuli set should be balanced
- Duration: singing is 14s long (avg)->long spectrogram
- Sex distribution is balanced
**Next things to check:**
- Acoustic feature distribution (Fo/harmonicity/spectral centroid/roughness/pitch variability) <- *would it be very easy to spot differences according to these features?*
- Recording quality and background sounds (folk singing has a lot)
- Speaker identity distribution
- Spectrogram appearance: static, use Emmalie's settings?

# 2 Labvanced
Reading: [Webcam eye tracking close to laboratory standards: Comparing a new webcam-based system and the EyeLink 1000](https://doi.org/10.3758/s13428-023-02237-8)

**Comparison**
*Tasks such as Blink task, Micro Saccades task, and Pupil Dilation task were excluded from the online adaptation for a number of methodological reasons.*

| Tasks                                          | Criteria                                                                                            |
| ---------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| 1.	Large Grid (fixation targets across screen) | accuracy, precision in the offset-related fixations, gaze data correlation, and data loss           |
| 2. Smooth Pursuit task                         | gaze data correlation (unbiased and not processed by any event detection algorithm)                 |
| 3. Free viewing of natural images              | gaze data correlation (unbiased and not processed by any event detection algorithm)                 |
| 4. Head movement – roll & yaw                  | how much these movements affected the ability of both eye tracking systems to produce reliable data |

[![Fig. 3](https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2d05/11289017/be5edf4595b0/13428_2023_2237_Fig3_HTML.jpg)](https://www.ncbi.nlm.nih.gov/core/lw/2.0/html/tileshop_pmc/tileshop_pmc_inline.html?title=Click%20on%20image%20to%20zoom&p=PMC3&id=11289017_13428_2023_2237_Fig3_HTML.jpg)

**Preliminary takeaway:**
- Webcam eye tracking can produce **comparable gaze patterns at a coarse level**, particularly for **fixation distribution and free viewing tasks**, but not for high-precision oculomotor measurements.

**Next step:**
- Evaluate whether our experimental design relies on **fine-grained eye movement measures** or only **coarse gaze distribution / attention patterns**.

# 3 Reading
1. Review of music visualization methods
	[A survey of music visualization techniques](https://doi.org/10.1145/3461835)
	[[@limaSurveyMusicVisualization2021]]
	- Intersection between MIR (music information retrieval) and InfoVis (information visualization)
	- two fundamental types: **augmented scores** and **performance visualization**
	- Survey about: 
		- what input was used; 
		- what feature(s) was/were visualized; 
		- which InfoVis technique(s) was employed; 
		- what was the proposal’s goals; 
		- how the users interacted; 
		- and evaluations of the visualizations proposed.
2. Crossmodal perception of voice
	- Most research on crossmodal perception of voice focuses on voice–face integration (e.g., audiovisual speech perception).
	- There appears to be much less work on abstract crossmodal correspondences involving vocal signals.

## 4 Web interface dev
(didn't have time yet, move to next week)