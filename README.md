# Convolutional Neural Network to Classify Retinal OCT Images (Fall 2020)
## Objective
Optical Coherence Tomography is a Retinal imaging technique used to detect retinal abnormalities. However, the analysis of such images to reach aretinal diagnosis serves to be a difficult and time-consuming task for medical professionals. This project aims to develop the most efficient convolutional neural network model to classify these OCT images. This CNN is then benchmarked against a fully-connected neural network model to demonstrate a CNN's performance in tasks that require spatial context.

## Background
OCT is a retinal imaging technique which uses light waves and their reflections to build a cross-section of the eye. This cross-section image is used to look at the different layers of the retina and identify any signs of abnormalities to diagnose optical diseases. For the purposes of this project, we focused on 4 types of classifications – Choroidal Neovascularisation (CNV), Diabetic Macular Edema (DME), Drusen present in Age-related Macular Degeneration (DRUSEN), and a Normal Retina (NORMAL). Figure 1 depicts an OCT Image of each of these abnormalities, along with a normal retina for a comparison

![OCT Image Example](./OCT_Image_Example.png)

## Online Demo
(tbd)

## Poster
![Image of Research Poster](./Poster.jpg)

## Folder Structure
- `week1` to `week3` contain example notebooks and exercises to get the group acquainted with the basics of ML.
- `OCT-cnn` contains notebooks to train many different models, as well as the weights for the most successful one.
