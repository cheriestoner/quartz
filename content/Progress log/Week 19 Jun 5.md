Goals:
- Lit review continue
- 2nd pilot data analysis
	- Quantify spectrogram features
	- Eye tracking heatmap shift?
- Live interface interview (scheduled next week)
---
## Literatures related to spectrogram reading/sound visualization

Soltani-Farani, A. A. (1998). Sound visualisation as an aid for the deaf, a new approach. University of Surrey. https://openresearch.surrey.ac.uk/esploro/outputs/doctoral/Sound-visualisation-as-an-aid-for/99516716702346#file-0

Kai-Hsiang Lin, Xiaodan Zhuang, Camille Goudeseune, Sarah King, Mark Hasegawa-Johnson, and Thomas S. Huang. 2013. Saliency-maximized audio visualization and efficient audio-visual browsing for faster-than-real-time human acoustic event detection. ACM Trans. Appl. Percept. 10, 4, Article 26 (October 2013), 16 pages. https://doi.org/10.1145/2536764.2536773


An interesting blog article by Dan Stowell – [On the validity of looking at spectrograms](http://mcld.co.uk/blog/2017/on-the-validity-of-looking-at-spectrograms.html "Permalink to On the validity of looking at spectrograms")
- The second example was particularly interesting, showing how hearing and seeing sounds can be fundamentally different:
> Another example which Trevor Agus sent me - I'll quote him directly: "My favourite counterexample for using the spectrogram as a surrogate for auditory perception is [Thurlow (1959)](http://asa.scitation.org/doi/abs/10.1121/1.1907630), in which he shows that we are rubbish at reporting the number of simultaneous pure tones, even when there are just 2 or 3. This is a task that would be trivial with a spectrogram. A more complex version would be Gutschalk et al. (2008) in which sequences of pure tones that are visually obvious on a spectrogram are very difficult to detect audibly. (This builds on a series of results on the informational masking of tones, but is a particularly nice example and audio demo.)"

## Labvanced eye tracking heatmaps issues:
Caspar (Labvanced CEO) responded to my questions, and basically, 
- positional shift is normal in eye tracking data
- the results from their Analysis (beta) is not 100% trustworthy
- I can no long have 1-1 calls with him; but he offers a general webinar to ENES

Caspar's full response as below:
> Hi Xuehua,
> Well support is not easy for a tool like ours. It's a fine line between overburden our team and basically stop working on anything but supporting users, vs being too restrictive. If you use your licensed account however, you should always get a fair and helpful level of support. In that regard I can't offer more 1:1 custom consultation calls, but only a general call for your entire lab (where we could do a  few minutes regarding your study)
> 
> To your question: Good to know that you like the functions of the analyzer. Just note it's in Beta and we currently don't have the capacity to explain much about it unfortunately. Once released we will of course offer more explanation. Note eve  our support team doesn't know much about it. We currently give it to a selected few internal and external users to learn how it's used and to improve it. If you have feedback  or suggestions please let me know . Also  I ask for your understanding  that for now the analyzer might not always work as expected. 
> 
> The fact that the gaze is shifted is normal. This is the normal error as it seems. Important  to know is long was your calibration? If you use the default settings such magnitude  of shift/ error is expected (~7%  error of screen diagonal) lf you use the longer calibration and a stricter chinrest the average error can drop to about half that (3-5%)  but some error  will always be there. 
> 
> All eye-tracking values are in frame units so when your iframe units were 800x450 (the default) 64 is about 7% because sqrt(800x800 +450x450) ~7%
> 
> I hope this can help.
> Best, Caspar


