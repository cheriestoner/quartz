---
aliases:
date: 2026-01-29
tags:
attendees:
---
**Three spectrographic softwares**
1. Desktop app, C++ (OpenGL), pixel-based, scientific tool
2. Browser-based, C++ w/ WebAssembly, pixel-based, for public use
3. (Hobby project) Browser-based, Javascript (WebGL, FFT.js), pixel-based
	*FFT.js is faster than Web Audio API*

**Technical problems & causes:**
1. Live spectrogram lagging
	- signal processing on CPU not GPU
		- bc spectrogram is drawn pixel-by-pixel
	- fft size too big
2. Bad resolution on spectrogram
	- need a good microphone

**Safe Git repo:**
- Gogs
- Currently private on GitHub, David/Emmalie decides if we publish the repo