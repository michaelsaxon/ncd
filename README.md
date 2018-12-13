# ncd
Nasal Cognate Distinctiveness family of features generation and preparation code

Based on Ming Tu, Junbo Zhang implementation of Kaldi Goodness of Pronunciation https://github.com/tbright17/kaldi-dnn-ali-gop

Very, very work in progress at this stage with regards to code cleaning, labelling, and commenting. Comments in most files need to be changed to reflect updated copyright.

Upcoming changes:
1. Execution script needs to be modified to call the post-processing python functions in order to generate a usable speaker-level NCD output feature.
2. Function names, folders, etc need to be changed to reflect the fact that this code is no longer computing Goodness of Pronunciation.
3. Comments in all files need to be changed to correctly ascribe copyright.
4. References to old feature name GON need to be removed and replaced with NCD.
