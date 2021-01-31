# Upgraded version of the RoboDog from Freenove

This repo includes some of the changes I made.

## Disclaimer

I guess first of all, this should be clear. I like the original Freenove Dog a lot. Go buy it if you enjoy working with robots and your Raspberry pi.
Furthermore I gonna try to explain my changes including their reason and the difficulties I had.
And last but not least, be aware that I'm no electric expert. There are surely some changes I made that will scare professionals a lot. So there is absolutely no guarantee this won't fry your Raspi. I don't give any warranty - but feel free to comment if you find anything that shouldn't be like that (or you have a better solution).


## Aims

When building the RoboDog I noticed some features missing I'd like to see implemented.

Aim was to create an "autonomous" Dog that behaves on it's own (in contrast to the App controlled one that comes delivered).
I therefore have/had to implement some additional funcitonality and remove / change others.

Some of the changes are discussed in the following sections:

1. Autonomous behavioural state machine - The RoboDog is supposed to walk around and react to incoming "impulses" such as detecting the discovered red ball, known faces etc.

2. Adding voice recognition  - Allowing the dog to listen to commands spoken. 

3. Giving the dog a voice - This aims on giving the dog a (primitive) option of feedback to the user. This would be sufficiently implemented by allowing playback of pre-recorded audio files.

4. Conceptual changes of the software / hardware - I noticed some aspects which I didn't like. Some where changeable, others not. I'd like to give some feedback and guidance for those here.

## Autonomous behavioural state machine 

## Adding voice recognition

## Giving the dog a voice

## Conceptual changes
