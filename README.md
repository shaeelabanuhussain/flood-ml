Playground Series S4E5
This repository contains my solution to the Kaggle competition "Playground Series S4E5".

Competition Overview:
The goal of this competition is to predict the target variable based on the provided dataset.

Dataset
The dataset consists of train.csv and test.csv files, which can be downloaded from the Kaggle competition page. The dataset contains the following columns:

id: Unique identifier for each sample
 'MonsoonIntensity',
    'TopographyDrainage',
    'RiverManagement',
    'Deforestation',
    'Urbanization',
    'ClimateChange',
    'DamsQuality',
    'Siltation',
    'AgriculturalPractices',
    'Encroachments',
    'IneffectiveDisasterPreparedness',
    'DrainageSystems',
    'CoastalVulnerability',
    'Landslides',
    'Watersheds',
    'DeterioratingInfrastructure',
    'PopulationScore',
    'WetlandLoss',
    'InadequatePlanning',
    'PoliticalFactors': Input features
target: floodprobability


notebook: googlecolab
you need to import train.csv file in google colab
You can run the inserted file copy_of_test4.ipynb in google colab
And get the necessary model downloaded from pkl or joblib


frontend: vs code
You may install streamlit library using pip install streamlit
Save your model in the working directory (used joblib)
and open new terminal and type streamlit run flood.py
If it does not redirect copy paste the localhost address given

competition link: https://www.kaggle.com/competitions/playground-series-s4e5/data
