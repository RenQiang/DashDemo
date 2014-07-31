DashDemo
========

Dynamic Adaptive Streaming over HTTP demo, inspired by Kangstantin Miller‘s description of algorithm in his paper 
"Adaptation Algorithm for Adaptive Streaming over HTTP".

The project can simulate the client-server interaction in DASH locally, using the algorithm described in Miller's paper,
simulating the bandwith situation using Markov Process. Data such as average bitrate can be recorded in time series while
simulation.

Project are restored in 3 directories respectly, the files restored in video directory are MPDs and video segmentations
with different resolutions; restored in dash directory is a html file giving the restriction of max bandwidth; in dash-js
are codes simulating the bandwidth situation and implemented the adaptive algorithm.
