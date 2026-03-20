Goals:
1. Improve live spectrogram interface
	- A tiny fade in window (one FFT window) at the start
	- spectrum->hue implementation 
	- Try TouchDesign for spectrogram
	- ANR deadline next Thursday
2. Design AI-human saliency comparison experiment
	- Ask Emmalie for assistance on human eye tracking?
	- CNN + fine tuning
	- Refine research question, scope, limitation-
3. Literature
	- Reading recommended by David https://www.sciopen.com/article/pdf/10.26599/JOTO.2025.9540003.pdf
	- Sensory substitution theories
---
# Live spec interface updates
Permanent link https://cheriestoner.github.io/Seeing-Voice/
Tinyurl https://tinyurl.com/mtptrzvn

1. Spectrogram animation: 
	1. Added a flash burst at the beginning of the spectrogram, to be more responsive to instant vocalisation
	2. Fade out starts sooner 32% -> 52%
	3. Scroll speed increased
	4. Scroll direction has two options <- and ->
	5. Color theme: added greyscale, "experimental" renamed into "crossmodal"
	6. Full screen planned, not implemented yet
2. FFT settings
	1. Frequency control has lin/log scale switch
	2. More presets coming... (planning, not implemented yet)
		- source pitch (0-600 Hz), speech (0-4000Hz), music (0-20k Hz), birds (10k-30k Hz), environment (x-x Hz to cover environmental noise?)
	3. Noise threshold: the lowest noise threshold is set to 3e-3, instead of the actual 0

# Literature review
Reading theories about sensory substitution (and augmentation), and developments in the field

***Brief history:*** 
1. **Early experiments** (60s-90s)
	Started in 1960s, by *Paul Bach-y-Rita* (tactile vision substitution)
	- **Methodology**: information representation/translation (early sensory substitution focused on encoding environmental signals from one modality (like vision) into a format accessible via another sense like touch)
	- **Theoretical basis:** brain plasticity, neural plasticity
	- **Limitation:** training is slow and intensive
2. **Expansion and refinement** (90s-00s-today)
	surrounding *the vOICe project* (started in the 90s by *Peter B.L. Meijer*, still ongoing till today, as a research network https://www.seeingwithsound.com)
	- **Methodology:** Improved early methods by integrating intuitive, crossmodal mapping -> sensory substitution works without prior training, for *static* information https://www.nature.com/articles/srep15628
	- **Theoretical basis:** 
		- Supramodal processing / representation: certain brain areas can extract abstract information (like shapes or spatial layouts) independent of the sensory channel
		- Sensorimotor/embodied perspective: perception arises not just from passive input but from active exploration
		- Learnability: mappings are designed to leverage natural *crossmodal correspondences* (e.g., pitch = vertical position, stereo = horizontal position), making interpretation more intuitive and reducing training
	- **Limitation / insight:** Crossmodal mappings improve learnability, but dynamic environments still require training.
3. **Modern (and future) perspectives:**
	sensorimotor contingencies by [J. Kevin O'Regan](http://nivea.psycho.univ-paris5.fr)
	- Focus shifts to leverage sensorimotor contingencies: sensory substitution as active perceptual skill acquisition, instead of passive translation of signals
	- Emerging applications:
		- sensory augmentation, assistive tech, neurorehabilitation
		- *even extended to robot multimodal learning & cognitive development* https://cyber.felk.cvut.cz/research/groups-teams/humanoids/

***General take-away:***
- Almost all sensory substitution research focused on "compensating/augmenting/expanding" **vision** (by tactile, auditory input) for the blind. None have touched "compensating/augmenting/expanding" **audition**
- Modern developments focus more on learnability (intuitiveness by natural crossnmodal correspondences) and widely uses the theoretical framework of **sensorimotor contingency theory**
# AI-human comparison study
(Didn't have time to start it yet)
