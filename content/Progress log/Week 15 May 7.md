Goals:
- Stimuli set: fix growl/roar designation
- Labvanced: design audio-image matching task
- Lit review: on audio visualization methods (not restricted to spectrograms)
- Lit review: crossmodal correspondences research by Ophelia Deroy
---
## Some discussions
**Experiment/user study on deaf children?** 
if they control the volume/pitch/... better using our spectro interface.
- possible to establish a long-term relationship with the deaf children association?
- longitudinal study over years?
- first study should be cautious? is the interface ready?
- apply for ethics?
*David: Deaf children studies are late-stage and not actually in the original plan (what did the original plan include exactly I forgot to ask)*
---
**Some examples of qualitative research papers in human-computer interaction field**
**(mentioned in my discussion with Kasia)**

1. Franklin Mingzhe Li, Michael Xieyang Liu, Yang Zhang, and Patrick Carrington. 2022. Freedom to Choose: Understanding Input Modality Preferences of People with Upper-body Motor Impairments for Activities of Daily Living. In Proceedings of the 24th International ACM SIGACCESS Conference on Computers and Accessibility (ASSETS '22). Association for Computing Machinery, New York, NY, USA, Article 39, 1–16. https://doi.org/10.1145/3517428.3544814
>[!note] In this paper (about designing for accessibility), the research questions were user-oriented design questions instead of scientific questions. For the methods, they used semi-structured interviews to find out the current challenges their user group was facing, preferences of their target users, and potential space for designing the tool. This is a typical HCI methodology.
2. Duesing SL, Lane-Karnas K, Duesing SJA, Lane-Karnas M, Y N and Chandna A (2025) Sensory substitution and augmentation techniques in cerebral visual impairment: a discussion of lived experiences. Front. Hum. Neurosci. 19:1510771. doi: [10.3389/fnhum.2025.1510771]([https://doi.org/10.3389/fnhum.2025.1510771](https://doi.org/10.3389/fnhum.2025.1510771))
>[!note] Haven't read it myself yet but it is relevant on the sensory substitution topic, and also uses qualitative interviews

As discussed with Kasia, I will start running one or two expert interviews in the lab next week, while documenting their free parameter manipulation strategies by their mouse movement (screen-recording) and talking (audio recordings). It will also be a semi-structured interview, where the experts (acousticians) are asked to perform certain tasks on human vocalizations and explain their thoughts during or after the process.

Kasia also suggested to design a an online quantitative experiment on the spectro interface. Participants will be designated to separate condition groups, by discrete options of **each** parameter of the spectro interface. The tasks will be to identify vocalisation functions. Performance will be compared across groups.

In the paper we might combine both qualitative and quantitative results? depending on the target journals

---
## Literature review: crossmodal correspondences
(will integrate in the google doc draft soon)
***Do crossmodal correspondences exist? How are they observed?***
crossmodal correspondences – the tendency for our brains (not to mention the brains of other species) to preferentially associate certain features or dimensions of stimuli across the senses. [[@spenceHowAutomaticAre2013]]

crossmodal correspondences are found affecting people's performance in a range of psychological tasks
- in everything from the redundant target-effect paradigm through to studies of the Implicit Association Test, 
- and from speeded discrimination/classification tasks through to unspeeded spatial localisation and temporal order judgment tasks. [[@spenceHowAutomaticAre2013]]

***What is "crossmodal correspondences"? Is it different from synaesthesia?***
- crossmodal correpondences and synaesthesia should be studies separately [[@deroyWhyWeAre2013]] [[@spenceCrossmodalCorrespondencesTutorial2011]]
- According to one influential review, synaesthesia can be **defined** as “a conscious experience of systematically induced sensory attributes that are not experienced by most people under comparable conditions” (Grossenbacher and Lovelace 2001, p. 36). [[@spenceCrossmodalMentalImagery2013]]
- a general **definition** of crossmodal correspondences *as acquired, malleable, relative, and transitive pairings between sensory dimensions* and to provide a framework in which to integrate the nonsystematic cataloguing of new cases of crossmodal correspondences, a tendency that has increased in recent years. [[@deroyWhyWeAre2013]]

**Table**: Summary of the differences between canonical cases of synaesthesia and crossmodal correspondences, which justify their distinction [[@deroyWhyWeAre2013]]

|                                                             | Synesthesia (canonical cases)                       | Crossmodal correspondences (most documented cases) |
| ----------------------------------------------------------- | --------------------------------------------------- | -------------------------------------------------- |
| Overt similarities                                          | Crossmodal inducing relation                        | Crossmodal mapping or matching                     |
|                                                             | Surprising                                          | Surprising                                         |
|                                                             | Consistent                                          | Consistent                                         |
| Differences (still compatible, with a difference in degree) | Rare                                                | From rare to frequent                              |
|                                                             | Idiosyncratic                                       | From idiosyncratic to universal                    |
|                                                             | Automatic                                           | Moderately automatic (control)                     |
|                                                             | Necessarily conscious                               | Not necessarily conscious                          |
| Key differences                                             | Absolute                                            | Relative                                           |
|                                                             | Unidirectional                                      | Bidirectional                                      |
|                                                             | Intransitive                                        | Transitive                                         |
|                                                             | Rigid                                               | Malleable                                          |
|                                                             | Not explainable by regular exposure                 | Explainable by exposure                            |
|                                                             | No good evidence in animals                         | Consistent with evidence in animals                |
|                                                             | No good evidence of conscious concurrent in infants | Consistent with behavioral evidence in infants     |

***Which crossmodal correspondences are found?***
- The majority of the studies of crossmodal correspondences that have been published to date have involved the presentation of **auditory and visual stimuli**. [[@spenceHowAutomaticAre2013]]
- auditory **pitch** has been shown to map onto 
	- visual elevation (see Ben-Artzi & Marks, 1995; Bernstein & Edelstein, 1971; Evans & Treisman, 2010; Melara & O’Brien, 1987; Miller, 1991; Patching & Quinlan, 2002; Proctor & Cho, 2006; Rusconi, Kwan, Giordano, Umiltà, & Butterworth, 2006), 
	- brightness and lightness (Hubbard, 1996; Ludwig, Adachi, & Matzuzawa, 2011; Marks, 1987; Martino & Marks, 1999; Melara, 1989; Mondloch & Maurer, 2004), 
	- size (Bien, ten Oever, Goebel, & Sack, 2012; Evans & Treisman, 2010; Gallace & Spence, 2006; Mondloch & Maurer, 2004; Parise & Spence, 2009, 2012), 
	- angularity of shape (Marks, 1987; Parise & Spence, in press), direction of movement (Clark & Brownell, 1976; Maeda, Kanai, & Shimojo, 2004; Sadaghiani, Maier, & Noppeney, 2009), 
	- and even spatial frequency (Evans & Treisman, 2010; Heron, Roach, Hanson, McGraw, & Whitaker, 2012). 
>[!note] **No** crossmodal correspondence has as yet been demonstrated between auditory pitch and visual contrast (Evans & Treisman, 2010) or between auditory pitch and hue (Bernstein, Eason, & Schurman, 1971). [[@deroyWhyWeAre2013]] [[@anikinImplicitAssociationsIndividual2018]]

**one more question: can (or how can) crossmodal visual stimuli (such as a spectrogram) induce a motor copy of human vocalisation which in turn generates an auditory activation?**

>[!quote] Quote from [[@spenceCrossmodalMentalImagery2013]] 
>"second, a kind of categorization of the inducer might be required to trigger the mental image in the other modality, but this categorization does not amount to a conceptual identification. Silent speech provides a good example of such a case, as the lip movements need to be recognised as speech-related movements (by contrast with, say, gurning movements) to induce an auditory activation and perhaps even as a general kind of phoneme to induce a more specific conscious concurrent. This form of categorisation is automatic and does not require any conceptual identification: If one accepts, for instance, the motor theory of speech perception (Liberman and Mattingly 1985), the visual stimulus triggers a motor copy of the lip movements, which in turn generates an auditory activation and, potentially, imagery episode, without any conceptual identification. In this sense, what we have here is a case of mediate crossmodal imagery, different from conceptually mediated imagery."
>[https://doi.org/10.1007/978-1-4614-5879-1_9](https://doi.org/10.1007/978-1-4614-5879-1_9)

---
## Plans with Emmalie
- Meeting next Monday at 10:30 to pick more roars from the dataset (to show the students in the afternoon)
- Meeting Christophe and students at 14:00 to discuss the AI classification
---
## Labvanced audio-image matching study
One audio + five spectrograms (each from a different category) -> one correct answer
Five spectrograms on a screen is too much for participants to comprehend?