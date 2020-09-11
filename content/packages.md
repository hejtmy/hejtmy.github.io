+++ 
draft = false
date = 2020-01-02
title = ""
slug = "" 
+++

### Navr
Navr is R based package which is made to work with positioning data in behavioral experiments. I have been using the package for analysing people's paths and behaviors in virtual environments, real environments and also for animal research with [rats and mice](https://github.com/hejtmy/fgu-avoidance).

- [github](https://github.com/hejtmy/navr)
- [documentation](http://hejtmy.com/navr/)

### BUF (BrainVR Unity Framework)
BrainVR unity framework is a product of 4 year long programming of various experimental paradigms in Unity and wanting to make the output and coding as much uniform as possible to simplify the code structure and data analysis pipelines.

The framework has functionality to organize the Unity experiments into understandable chunks and output fairly standardized behavioral data. The data can be then loaded using into R with the Brainvr reader package and quickly visualised and analysed. I also dabbed in uniform eye-tracking connectors as well as [sending live data](http://neuro-coder.com/gamedev/sending-information-unity-browser/) to the server, but those solutions were eventually replaced by more *ad hoc* solutions.

- [documentation](https://brainvr.github.io/brainvr-unity-framework-documentation/)
- [github](https://github.com/BrainVR/brainvr-unity-framework)
- [demo project](https://github.com/BrainVR/brainvr-unity-framework-demo)
- [brainvr reader](https://github.com/BrainVR/brainvr-reader)

### Eyer and eye-tracking
Eyer is a R based package which I started writing to uniform the analysis between several eyetracking systems we were using at the time. The package standardises the procedures and allows simple ROI analyses, visualisations etc.

There are also packages to parse and transform data to the *eyer* format from eye-tracker [SR 1000](https://github.com/hejtmy/eyelinkr) and [pupil labs](https://github.com/hejtmy/pupilr)

- [github](https://github.com/hejtmy/eyer)
- [documentation](http://hejtmy.com/eyer/)

### ggbgg

GGBGG is a *npm* hosted javascript pacakge to provide wrappers and parsers of boardgamegeek data. 

- [npm](https://www.npmjs.com/package/ggbgg)
- [github](https://github.com/hejtmy/ggbgg)