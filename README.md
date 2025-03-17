# Heart-Imaging-Genetic-Discovery

## Objective
In this project, we want to use the image features to find heart related Loci. 

![image](https://github.com/user-attachments/assets/7e4e7ace-9064-4774-947c-b611c9b2bf9c)


## Challenges

There is not heart template for registrating those MR images.

There are various image representations due to different MR scan machine, different scan protocol and different patients' heart situation.

There is no annotations for those heart images.

## Solutions

For heart image segmentation, we employ selective search and segment anything model 2 to generate the heart mask.

We use the heart mask to crop the original MR images into smaller ones, thus we can train a 3D model on them.

## Results

We get some heart related significant genes from these heart image features

## Tools

Pytorch, keras, Pandas, Numpy, Matplotlib, data visulization, SAM2, selective search.
