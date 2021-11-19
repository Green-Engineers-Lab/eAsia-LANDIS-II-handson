# eAsia-LANDIS-II-handson

<img width="1046" alt="image" src="https://user-images.githubusercontent.com/85103588/131287056-585abf9f-9e17-49f5-a1d8-b86543e8eed9.png">

# ITMoB Training Seminar Series #2: Modeling on Forest Landscape Change for Scenario Analysis
ITMoB launched a series of open online training seminars as an opportunity for technical capacity building.
The 2nd training seminar on forest landscape modeling will be organized on early December.
The program is designed for researchers and students who want to obtain the modeling skills for scenario analysis on forest landscape modeling.

Date: TBD

Time: 15:00-17:00 in Japan time（14:00-16:00 in Philippines time, 13:00-15:00 in Western Indonesian time）

Venue: Zoom (the link will be sent few days before to registered emails)

Language: English

Fee: Free

Information: https://supportoffice.jp/eAsia2021/events/

# Requirements
## Hardware
- OS == Windows 10 (64bit)
- PC memory >= 8GB
- Storage >= 10GB
## Software
- R >= 4.0.0
  - see, https://rstudio-education.github.io/hopr/starting.html
  - download "R" and "R-studio" matching to the specification of your PC
- Excel >= 2010


# Agenda
- The 1st session (Introduction and application)
  - 15:00-15:10 (JST) Opening remarks
  - 15:10-15:25 (JST) Introduction of LANDIS-II model
  - 15:25-15:40 (JST) Application of LANDIS-II model
  - 15:40-15:50 (JST) Q&A
- The 2nd session (Hands-on using Japanese dataset)
  - 16:00-16:15 (JST) Data requirement and Directory structure
  - 16:15-16:30 (JST) Simulation on landscape scale
  - 16:30-16:45 (JST) Analyze model output
- 16:55-17:00 (JST) Closing remarks

<!-- 

<img width="777" alt="image" src="https://user-images.githubusercontent.com/85103588/131470065-553735ea-2dc7-49b5-bce6-66d60c0d577c.png">


# Contents
<img width="708" alt="image" src="https://user-images.githubusercontent.com/85103588/131284597-7c278e28-c088-4c9a-a8ba-ff3a6d8eb6ff.png">

## The 1st session：Presentation about population distribution modeling
### 15:00-15:10 (JST) Opening remarks and introduction of ITMoB e-Asia project (Dr. Osamu Saito, IGES) (https://orcid.org/0000-0002-0697-9593)
![image](https://user-images.githubusercontent.com/85103588/131787720-5855c119-e296-4ebb-949e-717fde6b91db.png)

### 15:10-15:20 (JST) Population scenario development (Dr. Takanori Matsui, Osaka Univ.) (https://orcid.org/0000-0001-9441-7664)
#### 1. IPBES conceptual framework (https://ipbes.net/conceptual-framework)
<img src="https://user-images.githubusercontent.com/85103588/131281250-a924758c-4c14-4dd1-b8f6-5a321080b7c6.png" width="1000">

#### 2. PANCES (Predicting and Assessing Natural Capital and Ecosystem Services)simulation system for describing socio-ecological systems (http://pances.net/eng/theme1.html)
![image](https://user-images.githubusercontent.com/85103588/131280906-b1e1aa83-6557-47eb-925d-c4ddb95ff9e1.png)

#### 3. PANCES scenarios (https://link.springer.com/article/10.1007/s11625-017-0475-8)
![scenario](https://user-images.githubusercontent.com/85103588/131283167-edb2d7bb-113b-4dbc-9f7c-7c9cd6a7a676.png)

#### 4. Population forecasting of Japan (http://www.ipss.go.jp/s-info/e/ssj2014/001.html)
<img src="https://user-images.githubusercontent.com/85103588/131308192-05846671-dcd0-4edf-a88d-19a077b14923.png" width="1000">

#### 5. Training series
![series](https://user-images.githubusercontent.com/85103588/131285341-56db35a0-6e12-42c8-a868-8913f35dfde3.png)

#### 6. Two models for population projection
* The simple population model from Dr. Chihiro Haga (https://orcid.org/0000-0002-3325-6315)
* ![avatar](https://user-images.githubusercontent.com/85103588/131449796-4b229ac6-5d0b-4e5f-9d17-7bffd8230adc.jpeg)
* The demographic dynamics model from Dr. Keiko Hori (https://www.researchgate.net/profile/Keiko-Hori-2)
* ![Keiko-Hori-2](https://user-images.githubusercontent.com/85103588/131449800-4b09e6e8-732b-4940-879f-01c376e28bd7.jpg)






<img width="777" alt="image" src="https://user-images.githubusercontent.com/85103588/131470092-8fb3c1ba-f228-44eb-ab8f-a51a19a2a46b.png">




### 15:20-15:35 (JST) Development and application of gravity-based population allocation model (Dr. Chihiro Haga, Osaka Univ.)
#### Source: https://link.springer.com/article/10.1007%2Fs11625-018-0605-y  or preprint http://hdl.handle.net/11094/83603
#### Presentation material: [Presentation_ChihiroHaga.pdf](https://github.com/Green-Engineers-Lab/Population-Scenario-Project/files/7103531/Presentation_ChihiroHaga.pdf)

- What is gravity-based approach?
- Residential population distribution assumption of Compact & Dispersed scenarios
- Application: Overlay the future gridded population and socio-ecological status
### 15:35-15:40 (JST) Q&A

### 15:40-15:55 (JST) Development and application of combined model by cohort-component method and gravity-based method (Dr. Keiko Hori, IGES)
#### Presentation material: [Presentation_KeikoHori.pdf](https://github.com/Green-Engineers-Lab/Population-Scenario-Project/files/7103461/Presentation_KeikoHori.pdf)
#### Source: https://link.springer.com/article/10.1007%2Fs11625-020-00835-5
- Multi step model structure combining cohort-component method and grabity model
- Detailed mathematical algorithm and scenario assumption of each step
- Application: Overlay analysis on the future land use maps

### 15:55-16:00 (JST) Q&A

## The 2nd session：Demonstration of scenario analysis on grid population
![image](https://user-images.githubusercontent.com/85103588/131804918-f25039c2-6831-4201-8546-8e052bd5d466.png)

### 16:05-16:45 (JST) Scenario simulation of grid population by gravity model will be demonstrated
  Simulated experience will be provided for participants by shared dataset and codes. Indonesian data will be used as sample data for the demonstration.

#### 16:05-16:20 (JST) Step 1. Preprocessing population data (Dr.Haga)
- Data: 
  - Unconstrained age and sex structures in 2020 provided by [WorldPop](https://www.worldpop.org/geodata/summary?id=16850)
    - Citation: WorldPop (www.worldpop.org - School of Geography and Environmental Science, University of Southampton; Department of Geography and Geosciences, University of Louisville; Departement de Geographie, Universite de Namur) and Center for International Earth Science Information Network (CIESIN), Columbia University (2018). Global High Resolution Population Denominators Project - Funded by The Bill and Melinda Gates Foundation (OPP1134076). https://dx.doi.org/10.5258/SOTON/WP00646
  - Built-settlement extents, Indonesia provided by [WorldPop](https://www.worldpop.org/geodata/summary?id=17048)
    - Citation: WorldPop (www.worldpop.org - School of Geography and Environmental Science, University of Southampton; Department of Geography and Geosciences, University of Louisville; Departement de Geographie, Universite de Namur) and Center for International Earth Science Information Network (CIESIN), Columbia University (2018). Global High Resolution Population Denominators Project - Funded by The Bill and Melinda Gates Foundation (OPP1134076). https://dx.doi.org/10.5258/SOTON/WP00649
  - Constrained vs Unconstrained?
    - https://www.worldpop.org/methods/top_down_constrained_vs_unconstrained
- Processing in R & Rstudio
    1. Install & Load libraries
    1. Initialize parameters
    1. Read province & builtup area maps (in *step1_preprocessing_pop/data* folder)
    1. Iterate for each age & sex category
        1. Read population data (in *step1_preprocessing_pop/data/idn_westjawa* folder)
        1. Mask the population data within the west jawa province
        1. Remove non-residential area
        1. Compute proportion
        1. Save the raster data as dataframe in CSV format
    1. Merge all CSVs into one CSV file (*./output/step1_output_westjawa_cohort_data.csv*)
- For more technical tutorials, visit the following websites.
  - Learning R and Rstudio https://education.rstudio.com/learn/beginner/
  - Spatial Data Science with R, see https://rspatial.org/  and https://cran.r-project.org/web/packages/raster/raster.pdf
    - our tutorial use "raster" package not "terra" package
    
#### 16:20-16:35 (JST) Step 2. Calculate future population scenario (Dr.Hori & Dr.Haga)
- Data: projected 2045 population of West Jawa province by age groups and sex provided by [Indonesia Population Projection 2015-2045](https://www.bps.go.id/publication/2018/10/19/78d24d9020026ad95c6b5965/proyeksi-penduduk-indonesia-2015-2045-hasil-supas-2015.html)
- Open the Excel file named *ScenarioProj_Model* in *step2_generate_future_pop_scenarios* folder
    1. Click 'Enable Content' at the SECURITY WARNING bar
    1. Input arbitrary scenario name and parameters (γ and δ) at sheets *ParameterSetting_Compact* and *ParameterSetting_Dispersed*
    1. Push the button "Run" and wait few minutes (!!Don't touch anything until the calculation stop!!)
    1. Push the button "BAU allocater"
    1. Check the CSV files made at the folder *csv* with holding the scenario names 
 * You can find many tutorials to learn VBA more, such as https://www.tutorialspoint.com/vba/index.htm, https://www.guru99.com/vba-tutorial.html
        
#### 16:35-16:45 (JST) Step 3. Visualize & compare scenarios (Dr.Haga)
- Processing in R & Rstudio
    1. Install & Load libraries
    1. Initialize parameters
    1. Read the province map
    1. Iterate for each scenario
        1. Read the calculated population scenario from excel file (*step2_generate_future_pop_scenarios/ScenarioProj_Model.xlsm*)
        1. Add longitude & latitude information
        1. Rasterize the future population data
        1. Save the raster data
    1. Visualize the raster data using R / GIS software
        - see https://oscarperpinan.github.io/rastervis/

## 16:45-16:55 (JST) Q&A, feedbacks from participants
## 16:55-17:00 (JST) Closing remarks（Dr. Osamu Saito）
 -->
