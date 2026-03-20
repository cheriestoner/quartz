Goals:
1. VoiceID submission
2. Proof of concept for AI+human eyetracking study
3. Literature review

Meetings:
1. Christophe, IMLEX supervision (Monday)
2. Andrey, beyond speech stimuli set, study design (Tuesday)
3. Kasia & David, VoiceID abstract, study design (Tuesday)
4. Christophe, AI-human salience study (Friday)
---
## 1 VoiceID submission
Title: **Probing Human Interpretation of Vocal Spectrograms using AI Saliency Maps**
https://docs.google.com/document/d/1xnU0pVBO9oCEk5Y4DVY0Wr_Mhh95FVnF4PdEAvRJ0fU/edit?usp=sharing

submission date: March 13

General plan following this abstract:
1. Compare human and machine ‘eye tracking’ when performing the same task
2. Quantify the visual (and underlying acoustic information) that differentiates performance 
3. Test if imposing heatmaps (AI "focus") to raw spectrograms improves human performance, and vice versa? (imposing human eye tracking info for AI training?)
4. Explore how what we learn from AI heatmaps can be used to optimise spectrograms for human perception

## 2 AI-human salience study plan
### Dataset for ML training
- Amount (for CNN training): few hundred of samples for each class
- Type: nonverbal voice
- Directly usable contents from the Beyond Speech dataset: nonverbal vocalisation recordings, laugh 275 scream 214 roar 187 moan 118
### Proof of concept (not finished):
AI saliency maps have been widely used for visually explaining AI computing process in image analysis. Most "auditory intelligence"/sound analysis models use spectrograms as input, which are treated as images just like another picture of a cat.
Some existing research has applied the same XAI methods (AI saliency maps) for sound analysis. Several methods are examined in comparison with each other, on whether they can capture **biologically** and **acoustically** relevant information correctly (https://arxiv.org/html/2509.08717v1#S4.F6). 

**But no one has evaluated these methods systematically with human eyes.**

A few examples of the gradient class activation maps derived from CNN classifiers: the AI highlights relevant acoustic information
![[Pasted image 20260313182404.png]]
![[Pasted image 20260313182417.png]]
(source: https://medium.com/@beytullahyayla1/classifying-urban-sounds-using-2d-cnns-and-mel-spectrograms-f1aa049218c2)

## 3 Literature review
## (Pre-semantic) Voice processing in the brain
reading: https://linkinghub.elsevier.com/retrieve/pii/S1053811906000681
**Experiment conditions:**
Changing the source of the voice <- changing the **speaker**, 
Changing the salience of the voice <- changing the **amount of spectrotemporal detail**

**Processing hierarchy:** 
- general **source** attributes -> posterior superior temporal lobe, 
- abstraction of voice **identity** features -> posterior superior temporal sulcus (STS), 
- **further** analysis of voice information -> anterior superior temporal sulcus + higher order cortices in the middle and anterior temporal lobe.

-> Finding from the paper, : 
- source (speaker identity) analysis happens in the posterior superior temporal lobe 
- detailed voice info analysis happens in a bilateral network extending from the posterior to the anterior superior temporal lobe surrounding the superior temporal sulcus.

Other insights:
- While it is not possible to determine the **sequence of stages** of voice analysis from fMRI data, a **hierarchical organization** of cortical processing stages is supported by human functional imaging evidence.
- STS is likely to contain generic as well as voice-specific mechanisms: voice-specific and **cross-modal processes** involved in speaker recognition may occur at later stages of analysis (Nakamura et al., 2001; R ̈ama ̈ et al., 2004; Beauchamp et al., 2004; Lewis et al., 2004; Von Kriegstein et al., 2005; Fecteau et al., 2005).
> cross-modal here refers to *linking of vocal and facial identity*


---
# Meetings
## IMLEX student project supervision
**Student project:** Real-time isolation and localization of car horns in mixed reality
**Current status:** beginning stage, planning, doing literature review
**'Seeing sound' perspectives:**
- what are frequency characteristics of car horns?
- how can visualizations help users?
- how to highlight timing, distance, and direction in the visualization?
**Next meeting:** Mar 23, Campus Manufacture

## Andrey: sound stimuli and salience on spectrograms
- Auditory salience by Mounya Elhilali
	- early research look at visual salience on spectrograms
	- https://www.sciencedirect.com/science/article/pii/S0959438807000943
- Spectrogram, scalogram, cochleargram 
	- Implementations in soundgen: https://cogsci.se/soundgen/spectrograms.html#frequency-scale
	- Scale manipulation would be interesting: linear, log, mel, ERP (something like "half linear half log")
## Christophe: AI-human salience study
Relevant research by Christophe, on XAI: [https://ieeexplore.ieee.org/document/10647331](https://ieeexplore.ieee.org/document/10647331) reading cell images by AI

**Next steps for AI-human saliency study:**
- Use nonverbal vocalisations (laugh 275 scream 214 roar 187 moan 118) from Beyond speech dataset
- Download existing CNN models and do fine-tuning
- Visualize GradCAM (lower resolution than spectrograms) and overlay on spectrograms
- choose a small set of sounds to compare with humans