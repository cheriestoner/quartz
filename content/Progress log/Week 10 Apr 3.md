**Goals:**
- Continue on literature review
- AI-human comparison experiment
	- CNN + gradCAM
	- Program the pilot study for human part
		- Stimuli set: the same data subset for AI training->Nonverbal vocalisations: laugh (275) scream (214) roar (187) moan (118)
**Meeting**:
- with Kasia: feedback on literature review & experiment design
---
**Progress:**
# 1. Literature Review
Google doc: https://docs.google.com/document/d/1q8vtrXEUzSj74BiH5w-5vWLx8TjprnLTtfYLOi7rVhk/edit?usp=sharing
### Research Question:
*how can we exploit the cross-modal nature of voice perception for sensory substitution in the visual domain?*
### Brief Outline: 
1. The origin & evolution of human vocal communication
	- origin of voice
	- form-function framework
	- nonverbal vocalisations
2. Structured info encoded in voice
	- static info
	- dynamic info
3. The crossmodal/metamodal nature of voice perception
	- (todo) natural crossmodal perception in vocal communication: integration of facial expression with voice
	- sensorimotor contingency theory: perception is the mastery of sensorimotor laws independent of specific sensory pathways or brain areas
	- crossmodal correspondences: systematic, universal, low-level associations of crossmodal perceptual features
4. Visualization techniques
	- Different types of spectrograms
5. Embodied vocal learning with sensory substitution
	- Real-time visualization + training -> vocal learning through visual interface
## 2. AI-human comparison experiment
### Data preparation
Dataset:
- AI training and human experiment should use the same dataset (stimuli set)
- Selected subset from the Beyond Speech dataset
- Nonverbal vocalisations: laugh (275) scream (214) roar (187) moan (118) -> *the sample size reaches the minimum requirement for CNN model training* -> **still too many for human participants?**
- Pre-computed mel-spectrograms
### AI model
- Use convolution neural network (most popular for simple image processing)
- Fine-tuning using a pretrained model
	- [YAMNet](https://github.com/tensorflow/models/tree/master/research/audioset/yamnet)" – a pretrained deep net that predicts 521 audio event classes based on the [AudioSet-YouTube corpus](http://g.co/audioset)
## 3. Meeting details
[[2026-04-02 Kasia]]
**2026-04-01 Lunch conversation**
Paris speech therapist dyslexic children vocal learning (pronunciation & prosody) using pitch contour – passive reading of pitch contour of words
- pitch contour didn't work, possible reason:
	- Lack of real-time, embodied feedback?
	- Pitch contour is too simply, information scarce?
(Kasia emailed for more details)
---
**2026-04-02 Meeting 16:00-17:25**

**Agenda:**
- Literature review
- Labvanced experiment
- Emmalie's presentation
### Literature review
- Good style, concise, opinion-driven, as opposed to a comprehensive review of exhausted review
- Target journal: Trends in Cognitive Sciences, example: [[@pisanskiVoiceModulation2016]]
- Research question: more narrow, more focused
- Scope: theoretical grounding of the crossmodal nature of voice perception (not limited to assistive tech for the deaf)
- Collaborate with Emmalie
### Labvanced experiment
- Virgile's study on comparing human with random forest model
	- task: laughter classification
	- result: same accuracy
- Emmalie's presentation
	- Three sub-studies: emotion recognition/vocalisation type recognition/subjective feeling (beauty etc.)
- *New hypothesis about AI vs human:* 
	- AIs are better at accurate classification & local pattern recognition while 
	- humans are better at holistic feeling & high-level feature sensation (affective / aesthetic judgment)
	- *is it a valid guess?*
