### HyTwin -- New subclinical hypertensive multi-organ disease phenotypes identified from large-scale multi-national multi-modal datasets through contrastive machine learning 

#### Mohanad Alkhodari, Winok Lapidaire, Turkay Kart, Abhirup Banerjee, Paul Leeson
##### Cardiovascular Clinical Research Facility (CCRF), Division of Cardiovascular Medicine, University of Oxford, United Kingdom
##### Institute of Biomedical Engineering (IBME), Department of Engineering Science, University of Oxford, United Kingdom

###### Publication: Submitted to Nature Medicine (Status update soon)

Version: 1.1 Release date: 2025-08-5

###### Contact: 
✉️ mohanad.alkhodari@rdm.ox.ac.uk
✉️ winok.lapidaire@cardiov.ox.ac.uk
✉️ paul.leeson@cardiov.ox.ac.uk

<img src="https://github.com/malkhodari/HyTwin_academic/assets/62998803/4ef672ac-0dcd-4178-bfe6-e68c0f46a601" width="80%" height="80%">

<img src="https://github.com/user-attachments/assets/2024a9b5-eb8e-42b8-a7fe-0c0410e3c7d1" width="80%" height="80%">

<img src="https://github.com/user-attachments/assets/79c34273-944c-440c-b402-f2bafdee5847" width="80%" height="80%">

## 🔬 Details on HyperScore and HyperTrajectory modelling
```
- Hypertension is a serious medical condition that affects over a billion people worldwide
- The proper management of disease progression requires an extended knowledge on the functional/structural changes in the whole body in response to hypertension
- We developed the HyperScore; an integrative and unified measure of hypertension progression relative to multi-organ damage
- The HyperScore reflects the proximity of a participant from the healthy state and towards the diseased state [score range: 0 (low risk) – 1 (high risk)]
- We provide another level of characterization of the progression mechanism by locating the participant on a disease progression trajectory map, HyperTrajectory
- Each trajectory within the map reflects distinct hypertension-related end-organ progression pathway
- Trajectory 1: Cardiac disease, Trajectory 2: Lipoprotein diseases, Trajectory 3: Atherothrombotic diseases
- Trajectory 4: Brain diseases, Trajectory 5: Mortality, Trajectory 6: Liver Diseases
- The built-in model was developed using a large participating cohort from the UK Biobank database (n=27,099) with over 500 imaging/non-imaging variables from multiple modalities.
- It is based on a semi-supervised machine learning approach; the contrastive trajectory inference (cTI)
```

## 🛠️ Usage instructions
```
- Input dataset should be arranged to match the data provided in this example (demographics.csv and multimodality.csv)
- Once loading the demographics.csv file, the tool will arrange the multimodality.csv based on Patient IDs (row-wise)
- If no Patient IDs are provided, they will be refered to as numbers, i.e., 1, 2, 3, ... etc
- If Patient IDs are provided on one of the .csv files only, the other will be assumed to follow the same order
- The tool works with missing demographic variables, however, they will be replaced by NaN
- Ensure providing age, sex, and BP, if possible, if plots are required
- Ensure the inclusion of at least the UK Biobank variable id, i.e., 12338, in the name of each variable
- Variable names will be edited automatically to match with the built-in names within the tool, i.e., X12338_2_0
- The tool checks for missing variables in the dataset (please make sure to have all variables available!)
- The tool runs with missing variables, however, it would be more accurate if all variables were provided!
- Missing values will be imputed automatically using the big data (UKBiobank) at the back-end of the tool
- Run the trajectory inference to estimate HyperScores and predict the proper trajectory for each patient
- The overall analysis of the input dataset will be visualized on the right panel
- The user has the option to visualize the analysis for each patient separately as well
- Once done, the user can export all results (table and figures) as .csv and .png, respectively
```

## ☁️ For MATLAB online installation
[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=malkhodari/HyTwin_toolbox&file=HyTwin_academic.mlappinstall)

```
- Create a free MathWorks account or use an existing account (no license required)
- Sign-in with your account at MATLAB Online
- The link above will automatically obtain the files from the online repository
- Once MATLAB Online is open, select the tick box and click "Save and Open"
- The app will automatically download and ask you to install
- Once installed, click on the "Apps" tab on the top toolbar
- Click once on "HyTwin_academic" to open the online app
- Drag-drop patient files (in .csv) to the current path then hit browse
- You can manually adjust screen size based on your screen resolution (zoom out)
- You can add the app to favourites for faster access by clicking on the star
```

## 💻 For local MATLAB installation
```
- Create a free MathWorks account or use an existing account (no license required)
- Sign-in with your account at your local MATLAB
- Double-click or simply open Hytwin_academic.mlappinstall to install the toolbox
- Once installed, click on the "Apps" tab on the top toolbar
- Click once on "HyTwin_academic" to open the app
- Drag-drop patient files (in .csv) to the current path then hit browse
- You can manually adjust screen size based on your screen resolution (zoom out)
- You can add the app to favourites for faster access by clicking on the star
```

## 🔗 Learn more about us
https://www.rdm.ox.ac.uk/study-with-us/supervisor-profiles/leeson-group
https://eng.ox.ac.uk/multimedia/multimedia-people/
