[[2026-04-17 Seeing Sound ENES Team]]
## Pilot study
under Seeing Sound – MITI
### Labvanced experimental setup
**Current experimental design:**
- Stimuli: 40 Mel spectrograms per participant, 10 per class (laugh, scream, moan, roar), drawn from the Beyond Speech dataset  
- Classes: 4 (laugh, scream, moan, roar)  
- Trials: 40 per participant, 1 spectrogram per trial  
- Design: Within-subject, fully intermixed, randomized trial order  
- Eye tracking: Webcam-based (Labvanced built-in), 1 gaze recording per trial  
- Questionnaires: 1 pre-task (demographics, sensory profile, audio/spectrogram experience), 1 post-task (difficulty, confidence, strategy, audio awareness)

> Note: Following Kasia's suggestion, I will update the randomization so that each participant receives a different random subset of stimuli (stratified by class, 10 per class), rather than a fixed set of 40 shared across all participants.
> (currrently having technical issues on this)

**Feedback from Kasia and David:**
- Spectrograms are awful to read
- Eye tracking recalibration is tedious
### Machine learning model
Testing YAMNet
- Audio classification models' performance reply on **spectrogram configuration**. Spectrogram settings like freq scale, fft size etc. contribute to model training as hyper-parameters -> makes it tricky to "compare" models with humans on the same set of spectrogram images

## Live interface
- Added the full screen mode (more todo's in my codebase)
- Will setup the local interface in the sound booth next Monday with Romane (scheduled at 10 am 20 April)