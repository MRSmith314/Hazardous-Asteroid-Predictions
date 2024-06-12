<h1 align="center">DU - University of Denver<br/>
Data Analysis & Visualization Bootcamp<br/></h1>

--------------------------------

<h2 align="center">Group Project 4:<br/>
Asteroid Impact Prediction using<br/>
Supervised Learning and Neural Network Models<br/>
<br/>
By M. Aparisio, H. Heer, M. Smith & L. Vara</h2><br/>

![ReadmeImage_wText](https://github.com/maparisio/Asteroid-Impact-Prediction/assets/152572519/dd80ab66-bf53-44cd-a0a8-c50a6d454656)

Note: It is important that if you are going to use this code, all files
are placed in a directory that matches this repository, for the better functionality of it.
Otherwise you would have to adjust the paths on the files, accordingly.

This repository consists of a team project where we explore the predictability of asteroid impacts using machine learning models.

---------------------------------
INDEX
---------------------------------
1. Content of the repository
2. Instructions for the Project
3. References

---------------------------------
Content of the repository
---------------------------------
Original_Datasets:
impacts.csv
orbits.csv
h5_Files
Asteroid_Impact_Model.h5
Asteroid_Impact_Optimization_Model.h5
Asteroid definitions.pptx <-- Powerpoint presentation Intro to the project and definitions of the different columns in the dataset.
Asteroid_Predictions.ipynb <-- File started in Jupyter Notebook for data cleanup prior to Neural Network ML training
Asteroid_Predictions_Colab.ipynb <-- File worked on via Google Colab after cleanup, to train our Neural Network ML model prior to optimization.
Asteroid_Predictions_Optimization_Colab.ipynb <-- File worked on via Google Colab. Optimized version after training our Neural Network ML model.
asteroid-impact-prediction-SL-CFM.ipynb <-- File worked on via Jupyter Notebook for Supervised Learning, with unbalanced data.
asteroid_impact-prediction-SL-OverSample.ipynb <-- File worked on via Jupyter Notebook for SL, with OverSampling of the data.
asteroid-impact-prediction-SL-UnderSample.ipynb <-- File worked on via Jupyter Notebook for SL, with UnderSampling of the data.
cleaned_Asteroid_orbit.csv <-- csv file created via Jupyter Notebook after data was cleaned prior to creating the ML models (NN model version)

----------------------------------
Guide to the Project
----------------------------------
### Processes used 
1. Reading the csv files
2. Cleaning the data
3. Normalize and stabalize the data
4. Splitting the data
5. Training the Machine Learning models
6. Neural Network model implementation
7. Created a different Jupyter notebook with the same cleanup process to test Supervided Learning model
8. Supervised Learning model implementation
9. Confusion Matrix
10. Compared observations and search for improved accuracy for each model.

## Notebooks Used
Google Colaboratory
Jupyter Notebook

## Platforms, API’s, Libraries and Packages
Pandas
Matplotib
SciKit Learn
Tensorflow
Keras
Get_dummies
Seaborn
imblearn



------------------------------------
References
------------------------------------

**References for the data source(s):**
- Datasets for this project: https://www.kaggle.com/datasets/nasa/asteroid-impacts

**References for the column definitions:**
  - https://cneos.jpl.nasa.gov/about/neo_groups.html#:~:text=The%20vast%20majority%20of%20NEOs,%2Dmajor%20axes%20(%20a%20).
  - https://howthingsfly.si.edu/ask-an-explainer/what-orbit-eccentricity
  - https://en.wikipedia.org/wiki/Orbital_inclination
  - https://astronomy.swin.edu.au/cosmos/A/Argument+Of+Perihelion
  - https://cneos.jpl.nasa.gov/glossary/
  - https://www.britannica.com/science/mean-anomaly
 - https://en.wikipedia.org/wiki/Minimum_orbit_intersection_distance#:~:text=Minimum%20orbit%20intersection%20distance%20(MOID,collision%20risks%20between%20astronomical%20objects.

**References for code:**
- Uploading a CSV file to Google Colab: https://stackoverflow.com/questions/60347596/uploading-csv-file-google-colab
- Confusion Matrix Visualization: https://medium.com/@dtuk81/confusion-matrix-visualization-fc31e3f30fea
- Learning Rate Scheduler:
  https://machinelearningmastery.com/using-learning-rate-schedules-deep-learning-models-python-keras/
  https://keras.io/api/callbacks/learning_rate_scheduler/
  https://d2l.ai/chapter_optimization/lr-scheduler.html
  https://stackoverflow.com/questions/61981929/how-to-change-the-learning-rate-based-on-the-previous-epoch-accuracy-using-keras
  https://neptune.ai/blog/how-to-choose-a-learning-rate-scheduler
- Callbacks:
  https://www.kdnuggets.com/2019/08/keras-callbacks-explained-three-minutes.html
  https://medium.com/@ompramod9921/callbacks-your-secret-weapon-in-machine-learning-b08ded5678f0
  https://www.tensorflow.org/guide/keras/writing_your_own_callbacks

**Image Resources:**
- ReadMe image was taken from: https://pixabay.com/illustrations/dinosaurs-asteroid-stars-5568806/
- Slide images
-   https://pixabay.com/illustrations/asteroid-space-stars-meteor-1477065/
-   https://pixabay.com/illustrations/armageddon-apocalypse-earth-2104385/
-   https://en.wikipedia.org/wiki/Orbital_eccentricity
-   https://www.sciencedirect.com/topics/physics-and-astronomy/true-anomaly
-   https://www.researchgate.net/figure/Minimum-Orbital-Intersection-Distance_fig7_36174303
-   https://pixabay.com/illustrations/asteroid-planet-land-space-span-4376113/
-  NASA's Live Asteroid Watcher
  https://eyes.nasa.gov/apps/asteroids/#/home

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
