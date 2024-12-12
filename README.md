# Stable_Diffusion_Finetuning

## Authors: Osama Ahmed, Aarya Desai, Katie Hucker 

## Introduction 
This repository contains the notebooks and folders we used to train a baseline Stable Diffusion model and consequent finetuned models (using Textual Inversion and DreamBooth). 

## Stable Diffusion 2:
This was the base model used to generate images based on the prompts given (discussed in supplemental material). The code used for this can be found in the notebook `Stable_Diffusion_Base.ipynb`. This was run on Google Colab with a T4 GPU.

## Textual Inversion 
This was one of the finetuning methods used, which is further discussed in the supplemental material. The code used for this can be found in the notebook `textual_inversion.ipynb`. This was run on Google Colab with a L4 GPU.

## DreamBooth
This was the second finetuning method used, which is further discussed in the supplemental material. The code used for this can be found in the the folder `DreamBooth`. This was run on Google Colab with a T4 GPU.