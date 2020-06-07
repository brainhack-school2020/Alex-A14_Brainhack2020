[![](https://img.shields.io/badge/Visit-our%20project%20page-ff69b4)](https://school.brainhackmtl.org/project/template)

# Predicting Schizophrenia Diagnosis from Resting State fMRI

Team contributors: Alex(ander) Albury

![BrainHack School](bhs2020.png)

## Summary 

This repo contains the working project for Brainhack 2020

I'm a Psychology student at Concordia researching music cognition. I'm also interested in language science.

## Project definition 

### Background

This project will apply machine learning to predict schizophrenia diagnosis using fMRI data.

The data used is a resting state fMRI dataset of schizophrenia patients and healthy controls. The data comes from [The Center for Biomedical Research Excellence (COBRE)](http://fcon_1000.projects.nitrc.org/indi/retro/cobre.html).

This project aims to predict schizophrenia diagnosis using resting state data. Machine learning techniques will be used to classify schizophrenia patients from controls. The COBRE data set also includes subtypes of schizophrenia and so this project will predict diagnosis amonng schizophrenia patients. My goal for this project is to gain basic experience with processing/cleaning fMRI data. Following this, I'd like to experiment with different machine learning methods (algorithms, corss-validation methods, hyperparamters) and see how they compare.



### Tools 

The project will rely on the following technologies: 
 * This README is built in [Markdown](https://guides.github.com/features/mastering-markdown/), to structure the text.
 * Preprocessing will be done with `nilearn` and machine learning anlayses will rely on `scikit-learn`
 * The main summary and results of the project will live in a [Jupyter Notebook](https://jupyter.org/index.html) 
 * Adding the project to the website relies on github, through pull requests.

### Data 

The preprocessed data is publicly available on Nilearn and can be downloaded using `nilearn.datasets.fetch_cobre()` Documentation about the Nilearn data can be found [here](https://nilearn.github.io/modules/generated/nilearn.datasets.fetch_cobre.html#nilearn.datasets.fetch_cobre)

### Deliverables

At the end of this project, we will have:
 - A complete README summarizing the entire project and it results.
 - Week 3 Deliverable: 
     - [Plotly Histogram](http://htmlpreview.github.io/?https://github.com/brainhack-school2020/Alex-A14_Brainhack2020/blob/master/plotly.html)
     - Binder With ipywidgets Correlation Matrices (**Currently Debugging**) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brainhack-school2020/Alex-A14_Brainhack2020/master?filepath=visualization.ipynb)
 - A Jupyter notebook that contains all of the relevant code for project, properly formatted and commented.
 - A markdown formatted .md or .html document that contains code, descriptions, and visualizations from the project.

## Results 

### Progress overview

Currently the project includes a pipeline processing the demographic data and ensureing it's properly matched to the fmri files. There are also some visualiations of average brain activity for patients and controls.

### Tools I learned in this project:

 * **fMRI Data Processing with nilearn**
 * **Machine Learning with Scikit Learn**
 * **Interactive plotting with Plotly**
 * **Pandas Data Manipulation**
 * **fMRI Data Visualization**
 * **Visualizing Machine Learning Metrics**
 
### Results

![](https://webstockreview.net/images/coming-soon-png-images-6.png)

 
 
 
## Conclusion and Acknowledgements

TBD
