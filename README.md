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
You can run the inserted file DeepLearning (1).ipynb in google colab
save the weights file and json file needed for the front end


frontend: vs code
You may install streamlit library using pip install streamlit
Save your model weight and json files in the working directory
and open new terminal and type streamlit run app.py
If it does not redirect copy paste the localhost address given

competition link: https://www.kaggle.com/competitions/playground-series-s4e5/data
