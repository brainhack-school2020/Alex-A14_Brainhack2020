[![](https://img.shields.io/badge/Visit-our%20project%20page-ff69b4)](https://school.brainhackmtl.org/project/template)

# BrainHack 2020 fMRI/EEG/Machine Learning/Data Viz Project???

Team contributors: Alex(ander) Albury

![BrainHack School](bhs2020.png)

## Summary 

This repo contains the working project for Brainhack 2020

I'm a Psychology student at Concordia researching music cognition. I'm also interested in language science.

## Project definition 

### Background

This project will apply machine learning to predict music preferences and/or affective response to music.

Data will come from a combined EEG-fMRI task in which participants listened to music and continuously rated their feeling towards it. The study also included a behavioural survey of participant's preference for music genres. The published paper can be found [here](https://doi.org/10.1038/s41598-019-45105-2). Depending on the structure of the data, it might be interesting to try and predict preferences to music genre based on brain activity. While the data includes both fMRI and EEG, this project will focus on the fMRI data.

My goal for this project is to gain basic experience with processing/cleaning fMRI data. Following this, I'd like to experiment with different machine learning methods (algorithms, corss-validation methods, hyperparamters) and see how they compare. If the data is in the format I expect, it will be regression. (However, the rating scale of music preferences only goes to about 7 I beleive, so I suppose classification is also an option).

The scope of the project will ultimately depend on the amount of time spent preprocessing the fMRI data. If time allows, I can also compare algorithm performance across various regions of interest.

### Tools 

The project will rely on the following technologies: 
 * This README is built in [Markdown](https://guides.github.com/features/mastering-markdown/), to structure the text.
 * Preprocessing will be done with `nilearn` and machine learning anlayses will rely on `scikit-learn`
 * The main summary and results of the project will live in a [Jupyter Notebook](https://jupyter.org/index.html) 
 * Adding the project to the website relies on github, through pull requests.

### Data 

Data will be obtained from OpenNeuro.

The data I'm currently considering can be found here:
https://openneuro.org/datasets/ds002725/versions/1.0.0

It includes fMRI and EEG data for 21 subjects.

### Deliverables

At the end of this project, we will have:
 - A complete README summarizing the entire project and it results.
 - A Jupyter notebook that contains all of the relevant code for project, properly formatted and commented.
 - A markdown formatted .md or .html document that contains code, descriptions, and visualizations from the project.

## Results 

### Progress overview

The project is dependent on the available data. Next steps are to do some preliminary analysis of the data and confirm that the behavioural measures are available.

### Tools I'll learn during this project

 * **fMRI Data Processing with nilearn**
 * **ML with Scikit Learn**
 * **Pandas Data Manipulation**
 * **fMRI Data Visualization**
 * **Visualizing Machine Learning Metrics**
 
### Results

![](https://webstockreview.net/images/coming-soon-png-images-6.png)

 
 
 
## Conclusion and acknowledgement

TBD
