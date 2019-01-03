+++
# Project title.
title = "INSPIRE"

# Date this page was created.
date = 2019-01-02T00:00:00

# Project summary to display on homepage.
summary = "Combining molecular simulation and machine learning to guide precision cancer therapy."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Machine Learning", "Molecular Dynamics", "Cancer"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

The INtegrated and Scalable PredictIon of REsistanace (INSPIRE) project aims to lay the foundations for the use of molecular simulation and machine learning to guide precision cancer therapy.
The goal is to tailor treatment to provide maximum benefit to individual patients based on the genetic information about their particular cancer. 
In recent years, the development of targeted kinase inhibitors (which bind to proteins involved in signaling pathways that often control growth and proliferation that become dysregulated in many cancers) has changed the way many cancers are treated. 
Unfortunately, the development of resistance to these therapies limits the amount of time that patients can derive benefits from their treatment. 
Resistance to therapeutics is responsible for more than 90% of deaths in patients with metastatic cancer. 
The use of predictive simulation is vital to such an approach as the vast majority of clinically observed mutations are rare, essentially ensuring that it will be impossible that catalog-building alone will be sufficient for making therapeutic decisions.

We propose to develop and benchmark the framework for scalable accurate, rapid and predictive computational models to identify whether clinical mutations in kinases confer resistance or susceptibility to small molecule kinase inhibitors by modulating inhibitor affinity. 
We employ two complementary technologies: 

  1.  Machine learning models that utilize a problem-adapted featurization to allow both large existing kinase affinity datasets and sparser clinical datasets
  2.  Physical modeling approaches that are applicable even in the absence of large clinical datasets. 
  
These approaches are complementary in that the more expensive physical modeling approach (2) can be used to generate additional targeted data for the machine learning approach (1) to improve its predictive accuracy at the expense of up-front computational effort.

The INSPIRE project was awarded a major allocation of super computer resources (80 million core hours on [Titan](https://www.olcf.ornl.gov/olcf-resources/compute-systems/titan/) at the Oak Ridge National Laboratory) through the US Department of Energy [INCITE](http://www.doeleadershipcomputing.org/incite-awards/) Supercomputing Award. 
INSPIRE is a collaboration that brings together our [CCS](http://ccs.chem.ucl.ac.uk/) team at UCL, working on binding affinity predictions, with three academic groups from the US and the pharamaceutical company Janssen.
The [Chodera lab](http://www.choderalab.org/) from the Memorial Sloan Kettering Cancer Center in New York City brings expertise in studying kinase systems using both computational and experimental techniques.
[Rick Stevens](https://www.anl.gov/cels/person/rick-stevens) (Argonne National Laboratory and the University of Chicago) leads the Deep Learning Enabled Precision Medicine for Cancer project, [CANDLE](http://candle.cels.anl.gov/), in collaboration with four DoE labs and the National Cancer Institute. 
Dr Herman Van Vlijmen and his team from Janssen provide open datasets from kinase inhibitor discovery projects. 
The [RADICAL](http://radical.rutgers.edu/) group (headed by Prof Shantenu Jha) at Rutgers provides the middleware which facilitates the combination of HPC (high performance computing) with HPDA (high performance data analytics) involved in this project.