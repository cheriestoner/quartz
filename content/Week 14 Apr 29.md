# Labvanced experiment
**New stimuli set:** 
Nonverbal vocalisations collected, processed, and labelled by Emmalie.

100 audio clips of non-verbal human vocalisations, curated and amplitude-normalised, organised into 5 vocalisation types with 20 clips each, labelled with affective, communicative context.

| Vocalisation | Emotion / context | n |
|--------------|-------------------|---|
| Cry | sad | 19|
| | pain | 1 |
| Growl / Roar | effort | 7 |
| | anger | 5 |
| | pain | 4 |
| | disgust | 3 |
| |exams (achievement)| 1 |
| Laugh | amused | 15|
| | malice | 5 |
| Moan | birth | 13|
| | sex | 7 |
| Scream | anger | 6 |
| | pain | 7 |
| | fear | 5 |
| | fear-bungee | 2 |

**New study on labvanced:** [https://www.labvanced.com/player.html?id=83743](https://www.labvanced.com/player.html?id=83743)

**To be discussed:**
- Normalisation: audio clips were normalised by peak amplitude (according to Emmalie)
- Silence trimming: Clips have long leading/trailing silences. Kasia suggested trimming to 500ms before/after the vocalisation
- Vocalisation type vs. affective context as classification targets
- Growl/roar category: 
	From Kasia: We will have to think carefully about the interpretation of our results as we have divided the vocs based on their 'type' (e.g., moan) rather than their function per se. For example, for moans, we have both childbirth (pain) and sex (pleasure), for laughs we have both amused (positive valence) and malice (negative), for screams we have both fear (subordinate) and anger (dominant), etc. Each vocalisation group contains stimuli that were produced in several different contexts. Technically these should sometimes differ in their acoustic forms, as shown by Virgile's work for laughter for example (Daunay et al., 2025 jasa). 
	Can we all discuss the *designation of growl/roar*? These are two different vocalisation types. I listened to the 20 growl/roar stimuli and agree they are hard to differentiate because both are harsh and low-pitched, but there are important differences, too: growls usually have less airflow than roars, making them quieter, and are more often produced with a closed mouth whereas roars are more 'explosive'. Should we really group them together? 
	Also the affective contexts in this category include anger, disgust, effort and pain. To be honest, the 'disgust' vocalisations sound more like 'gags' or even moans to me, not roars or growls. It's strange to think of a 'roar of disgust' or 'growl of disgust', same with 'growl of pain'. Where did the labels for these roar/growl voc types originate from (Andrey?)
	(*about whether to drop the growl/roar category as it is different to differentiate them even by listening:*) 
	Our research has shown they are highly relevant for communicative threat, dominance, size etc., and show strong form-function mappings that parallel what we observe in other mammals. So, another idea I had was just to drop the 'growls' (far less studied in humans) and retain only the roars, adding a few others to reach the original n=20.
- Origin of vocalisation labels: is it from a published taxonomy?
# Live spectro interface
https://cheriestoner.github.io/Seeing-Voice/
- Added more user control blocks for
	- Background color: dark/transparent
	- Fade out speed & flash boost intensity at the start
- Todo: more frequency ranges (mel etc.) & more frequency range presets

# Literature research
from The Oxford Handbook of Voice Perception
>[!quote] Working definition of a *voice*
>A voice is an acoustic signal produced by the anatomical and physiological vocal tract system in a variety of vertebrate species or equivalently modelled and simulated in technical systems. This signal is acoustically registered and auditorily perceived mainly by conspecifics, and is detected, rated, and potentially classified as a distinctive vocal auditory object or as a distinctive voice feature depending on its specific voice quality compared to other auditory objects.

still reading the book to look for hints about what "the **auditory object** that is perceived as a voice" is, to further answer what can be captured by visual forms

spectrograms preserves the acoustic structure faithfully, but what is missing (socially relevant info, contexts) and what might be redundant for voice perception?
- from (Daunay et al., 2025 jasa), "laughter acoustics (fundamental frequency, acoustic energy, and temporal regularities) can encode contextual information that is detectable by both machine algorithms and human listeners, but not with high precision", but is the acoustic structure of a single *isolated* vocalisation enough for determining the context? and how can the real-time visualization enhance the affective communication in context?

