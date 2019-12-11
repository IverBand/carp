# Chronic Absenteeism Rate Prediction (CARP)
This was my capstone project for the Coursera Advanced Data Science with IBM Specialization. It demonstrates all phases of a data science project, including modeling with a neural network and a decision tree ensemble using Keras and scikit-learn.

To get started:

1. In the docs directory, view the project presentation, Chronic Absenteeism Rate Prediction.pdf to familiarize yourself with the project. Optionally, read the accompanying architectural decisions document.

2. Place the five Jupyter notebooks where you plan to execute them.  If you are using IBM Watson Studio, upload them to your project.

3. If you are using IBM Watson Studio, upload all files in the data directory to the object store, and make them assets of your project.  Otherwise, place all data files in the same directory as the Jupiter notebooks.  

4. There is one data file that is too big to share on github.  It is the shapefile and associated metadata for the census tracts in the US state of California.  These files are available as one big (29 MB) zip file at 
https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2018&layergroup=Census+Tracts 
Point your browser to this URL, select California in the dropdown menu, and click submit to download the file, which is called tl_2018_06_tract.zip.  Then, either upload it to IBM Watson Studio as a project asset, or place it in the same directory as the Jupyter notebooks. Do not unzip the file.  The CARP-EXP notebook takes care of that.

5. If your are using IBM Watson studio, edit the notebooks and insert project tokens by clicking on the three-vertical-dot icon in the upper right of the notebook page.

6. Some of the notebooks install their own modules.  Depending on the contents of the Jupyter kernel you are using, you may want or need to adjust these cells with !pip commands.

6. Execute the notebooks for the first time in the following order:

    a. CARP-ETL - Extract, Transform, and Load
    b. CARP-EXP - Data Exploration
    c. CARP-DNN and CARP-DTE - Deep Neural Network and Decision Tree Ensemble - either may be executed first
    d. CARP-ME - Model Evaluation
  
  Enjoy!
  
  Iver
