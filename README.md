# About Dataset

## Context

This dataset was originally for a machine learning challenge to classify heart beat sounds. The data was gathered from two sources: (A) from the general public via the iStethoscope Pro iPhone app, and (B) from a clinic trial in hospitals using the digital stethoscope DigiScope. There were two challenges associated with this competition:

1. Heart Sound Segmentation

The first challenge is to produce a method that can locate S1(lub) and S2(dub) sounds within audio data, segmenting the Normal audio files in both datasets.

2. Heart Sound Classification

The task is to produce a method that can classify real heart audio (also known as “beat classification”) into one of four categories.

## Content

The dataset is split into two sources, A and B:

- set_a.csv - Labels and metadata for heart beats collected from the general public via an iPhone app
- set_a_timing.csv - contains gold-standard timing information for the "normal" recordings from Set A.
- set_b.csv - Labels and metadata for heart beats collected from a clinical trial in hospitals using a digital stethoscope
- audio files - Varying lengths, between 1 second and 30 seconds. (some have been clipped to reduce excessive noise and provide the salient fragment of the sound).

## Acknowledgements

@misc{pascal-chsc-2011,
author = "Bentley, P. and Nordehn, G. and Coimbra, M. and Mannor, S.",
title = "The {PASCAL} {C}lassifying {H}eart {S}ounds {C}hallenge 2011 {(CHSC2011)} {R}esults",
howpublished = "http://www.peterjbentley.com/heartchallenge/index.html"
}

css


## Inspiration

Try your hand at automatically separating normal heartbeats from abnormal heartbeats and heart murmur with this machine learning challenge by Peter Bentley et al.

The goal of the task was to first (1) identify the locations of heart sounds from the audio, and (2) to classify the heart sounds into one of several categories (normal v. various non-normal heartbeat sounds).
