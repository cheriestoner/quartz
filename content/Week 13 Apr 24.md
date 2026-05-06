***Meetings***
Emmalie, Mon, Apr 20
- MITI Eye tracking study
	- Manually select clean spectrograms as stimuli /Emmalie & Xuehua
	- Labvanced + Tobii /Emmalie
	- Sync progress with Christophe & Eric (Eric proposed Wednesday 6 May meeting for eye tracking experiment)
Emmalie, Fri, Apr 24 (postponed)
---
***Goals***
- Clean stimuli set
- YAMNet audio classification transfer learning
- Literature review reframing: existing story + amodal cues & spectrogram representations
- Technical setup for the whistling study
-  VoiceID registration?
---
***Literature review reframing:***

***1. Foundational question***:
**What is auditory perception? Can it be instantiated in another modality & how can we construct an audition-like perceptual experience in vision?**

An unresolved debate about sensory substitution: *do they really involve perceptual experiences similar to the source modality, or are based on higher-level cognitive decision strategies for stimulus discrimination?*

The sensorimotor contingency theory ([J. Kevin O'Regan & Alva noë, 2001](https://link.springer.com/article/10.1023/A:1012699224677#auth-J__Kevin-O_Regan-Aff1)) frames a strong theory of what the perception fundamentally is:
>[!quote] Perception is the mastery of sensorimotor laws through that govern the relation between possible actions and the resulting changes in incoming information in that sense modality

On this view, perception is not a passive reception of data but an active skill — and in principle, any modality could instantiate any perceptual experience, provided the right sensorimotor contingencies are preserved. This is theoretically compelling, and potentially the closer account of what perception actually is. But it faces a deep practical problem: for audition specifically, the temporal nature of sound makes it unclear what the relevant contingencies even are. Unlike vision — where moving your eyes predictably shifts the scene — sound doesn't persist in space for active exploration.

[Deroy & Auvray (2012)](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2012.00457/full) propose a practical framework for sensory substitution studies. They argue that sxisting devices have failed to approach the speed, accuracy, or richness of non-impaired perception, and fall far short of producing anything like genuine cross-modal experience. Rather than treating this as a temporary engineering limitation, they propose a theoretical reframing –– sensory substitution is better understood through an analogy with reading:
>[!quote] The skills achieved with sensory substitution devices should not be interpreted as being ‘perceptual’ but rather should be  described as “acquired cognitive extensions to existing perceptual skills”

***2. Research question:***
**How can we exploit the cross-modal nature of voice perception for sensory substitution in the visual domain?**
more precisely:
**How can the social and affective meaning of voice be conveyed through visual representation — and what does this reveal about the cross-modal nature of voice perception?**
if we adopt Deroy & Auvray's framework as our working assumption, the research question can be re-formulated as:
**How can visual representations of voice support the development of perceptual skills for reading its social and affective meaning — and what does this reveal about the cross-modal nature of voice perception?**

***Sub-questions:***
- **How do humans jointly perceive multiple social and affective dimensions of a voice (identity, emotion, warmth, dominance, vocal type, etc.)?**
    - What acoustic features carry each of those dimensions — and do they overlap, compete, or occupy separate parts of the signal?
    - Is there a low-dimensional "voice space" structuring how voices vary socially and affectively — and does any current representation approximate it? (like the valence-arousal space of affect?)
    - *Reading list: The Oxford Handbook of Voice Perception, papers by Kasia Pisanski, Greg Bryant, Andrey Anikin, Elodie F. Briefer, Scott Sophie, Carolyn McGettingan*
- **Are there amodal cues in voice — features that carry social and affective meaning independently of sensory channel?**
    - Which perceptual dimensions are candidates — roughness, warmth, dominance, pleasantness, attractiveness?
    - *Reading list: Roughness perception (Stefano & Spence),*
    - Do amodal cues map onto the acoustic features identified above, or do they cut across them in unexpected ways?
    - Do spectrograms already encode amodal cues –– is the information present in the signal? 
    - Can humans perceptually recover amodal meaning from a spectrogram without hearing the sound?
	- *Reading list: ?*
- **What would it mean for a visual representation to successfully encode an amodal cue — and where does the bottleneck lie?**
    - Is the bottleneck in the representation, or in how humans dynamically integrate cues in real time?
	    - The voice is a time-varying social signal processed holistically — any representation must preserve temporal dynamics to remain meaningful
	    - This is fundamentally a question about the theory of what the signal means, not just signal processing
	- *Reading list: papers about sensorimotor theory in auditory perception (in my Zotero folder)*
- **How to design a dynamic visual representation that makes amodal voice cues perceptually accessible?**
	- *This question is more for empirical and design research, and less for literature research*
    - What are the design requirements that follow from the perceptual science above?
    - How do we evaluate whether a visualization succeeds — by what perceptual or behavioral criteria?