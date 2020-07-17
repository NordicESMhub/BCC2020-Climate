class: center, middle

# Getting your hands-on Climate data

## Anne Fouilloux
## University of Oslo, Norway

---

##  How we will operate?

### Registration/Login to Galaxy Climate

- We will be using Galaxy Climate https://usegalaxy.eu/ for this tutorial
- If you have already registered to Galaxy Europe ([https://usegalaxy.eu/](https://usegalaxy.eu/) then you are ready to go
- Otherwise, please register before we start at [https://usegalaxy.eu/login](https://usegalaxy.eu/login).

### Join Climate training group

- Please go to the following URL:

[https://usegalaxy.eu/join-training/gcc-climate](https://usegalaxy.eu/join-training/gcc-climate)

You will be added to the training group and put into a private queue which should be a bit faster than our regular queue. Our training queue will be available from 2020-07-17 to 2020-07-19. 


---

## Agenda


- Short presentation on the topic
- Presentation of the training material [Getting your hands-on climate data](https://training.galaxyproject.org/training-material/topics/climate/tutorials/climate-101/tutorial.html)
- Introduction of the datasets
- Galaxy tools you can use for the hands-on
- Hands-on exercises: 
    - You work on the provided material, feel free to dicuss within others,
    - Use the collaborative document to indicate when you are done with an exercise,
    - Should you have any problem, please use the *chat*,
    - I have set-up a **get help table** that you can visit whenever you need individual support.

---

## What we mean by "Climate"?

<img src="word_cloud.png" width="50%" />

To make sure we all have the same understanding:

*According to [wikipedia](https://en.wikipedia.org/wiki/Climate), Climate is defined as the **average state** of everyday’s weather condition **over a period of 30 years**. It is measured by assessing the patterns of variation in temperature, humidity, atmospheric pressure, wind, precipitation, atmospheric particle count and other meteorological variables in a given region over long periods of time. Climate differs from weather, in that weather only describes the short-term conditions of these variables in a given region.*


---

## Weather versus climate

Watch [this Video](https://youtu.be/e0vj-0imOLw) to get an illustration of the difference between climate and weather.

<img src="https://training.galaxyproject.org/training-material/topics/climate/images/weather_versus_climate.png" width="80%" />

Source: [Animated short on statistics](https://youtu.be/e0vj-0imOLw) from Norwegian infotainment program Siffer. Produced by TeddyTV for NRK. Animation by Ole Christoffer Haga


---

## Types of climate data resources

- Observations
- Re-analyses
- Climate models

We have very little actual observations at the scale of climate and usually not covering a large area. 

The type of climate data you will be using greatly depends on the period of time you are interested in.

<img src="https://nordicesmhub.github.io/climate-data-tutorial/fig/climate_data_types.png"  width="50%" />

---

## Observations

## Direct observations

These are measurements (from ground stations, buoys, satellites, etc.) of one or more physical variables (temperature, humidity, wind, etc.) at one or more particular times and places. 

<img src="https://nordicesmhub.github.io/climate-data-tutorial/fig/WMO%20Global%20Observing%20System.png" width="60%" />

Source: https://uls.climate.copernicus.eu

---

## Indirect observations

They are derived from other observations:
- ice cores
- lake sediments
- tree rings

These are sometimes referred to as "climate proxies"

<img src="https://nordicesmhub.github.io/climate-data-tutorial/fig/frost_rings_375.jpg" width="40%" />

Source: https://www.earth.columbia.edu

---

## Models

Numerical models are a mathematical representation of the climate developed by scientists to understand and predict the climate system. 

<img src="https://www.climate.gov/sites/default/files/AtmosphericModelSchematic.png" width="68%"/>

Source: [https://www.climate.gov/maps-data/primer/climate-models](https://www.climate.gov/maps-data/primer/climate-models)

---

## Re-analyses

A climate re-analysis gives a numerical description of the recent climate, produced by combining models with observations. It contains estimates of the air temperature, wind at different altitudes, rainfall, soil moisture content, etc.
The estimates are produced for all locations on earth, and they span a long time period that can extend back decades or more.


## Climate models

Various types of models are used for different aspects of the climate. 
All have different ways to represent the real world, depending on how researchers prioritize and perform these simplifications (in terms of parameterizations, etc.) in the numerical climate model.
We usually do not use one model only but severals that we combine together: the collective results give a better overview of the real world than any single model.

### How good are climate models?

- Climate models are improving
- Climate models have "biases"

---

## Climate prediction *vs.* projection

### Climate prediction

A **climate prediction** (or climate forecast) is an attempt to produce an estimate of the actual evolution of the natural climate in the future, for example, at seasonal, inter-annual or long-term time scales. 

### Climate projections

**Climate projections** are distinct from climate predictions in that projections depend upon emission/concentration/radiative forcing **scenarios**, which are based on assumptions concerning, for example, future socio-economic and technological developments that may or may not be realized and are therefore subject to substantial uncertainty.

Within the Coupled Model Intercomparison Project (CMIP), now in its 6th phase, project simulations of the research community provide model output that will fuel climate research and climate impact studies for the next 5 to 10 years, while its careful analysis will form the basis for future climate assessments

---

## Shared Socio-economic Pathway (SSP)


**= societal development pathway**

The SSPs were developed as a joint community effort and describe global developments that
together would lead to different challenges for mitigation and adaptation to climate change.
SSPs comprise **five alternative** narratives that describe the main characteristics of the
pathways in qualitative terms as well as quantitative descriptions for key elements including
population, economic growth and urbanization.

---

## SSPs and Shared Policy Assumptions (SPAs)

- [SSP1 Sustainability](https://en.wikipedia.org/wiki/Shared_Socioeconomic_Pathways#SSP1:_Sustainability_(Taking_the_Green_Road)): Taking the Green Road e.g. low challenges to mitigation and adaptation

- [SSP2 Middle of the Road](https://en.wikipedia.org/wiki/Shared_Socioeconomic_Pathways#SSP2:_Middle_of_the_road):  Medium challenges to mitigation and adaptation

- [SSP3	Regional Rivalry](https://en.wikipedia.org/wiki/Shared_Socioeconomic_Pathways#SSP3:_Regional_rivalry_(A_Rocky_Road)): A Rocky Road e.g high challenges to mitigation and adaptation

- [SSP4	Inequality](https://en.wikipedia.org/wiki/Shared_Socioeconomic_Pathways#SSP4:_Inequality_(A_Road_Divided)): A Road Divided e.g. low challenges to mitigation, high challenges to adaptation

- [SSP5	Fossil-fueled Development](https://en.wikipedia.org/wiki/Shared_Socioeconomic_Pathways#SSP5:_Fossil-Fueled_Development_(Taking_the_Highway)): Taking the Highway e.g. high challenges to mitigation, low challenges to adaptation

---

## SSPs and Shared Policy Assumptions (SPAs)


<img src="SSP_scenarios.png" width="105%" />

---

## Where to start

*There is a wealth of data and information available on the **web** about the past, current and future climate.*

**Not all of it is up-to-date and trustworthy**

- Check the provenance and data provider credentials

**Not all the variables/parameters are necessarily relevant for your study**

- Prioritize the use of Essential Climate Variables

**Not all the variables are reliable**

- Prioritize observations and re-analyses for past climate

**Prefer authoritative data providers**

---

## Training material

- Tutorial is available through <img src="docs.png" />
- Video with step by step tutorial on the left panel
- Slides are available through <img src="slides.png" />

---

## Datasets

- Downloaded from [European Copernicus Climate Change Service (C3S)](https://climate.copernicus.eu/)
- Data format:
	- Most common data format for Climate data is called [netCDF](https://www.unidata.ucar.edu/software/netcdf/) e.g. Network Common Data Form
	- But converted to *csv*/*tabular* data format to ease their usage

- [tg_ens_mean_0.1deg_reg_v20.0e_Paris_daily.csv](https://zenodo.org/record/3776500/files/tg_ens_mean_0.1deg_reg_v20.0e_Paris_daily.csv)
- [ts_cities.csv](https://zenodo.org/record/3776500/files/ts_cities.csv)

---

## Galaxy tools

- Select lines that match an expression
- Datamash
- Text reformatting with awk
- Scatterplot w ggplot2
- climate stripes from timeseries
- Copernicus Essential Climate Variables
- map plot gridded (lat/lon) netCDF data
- NetCDF xarray Metadata Info

---

# Hands-on

## Collaborative document

We will be using a collaborative document:
- where participants can introduce themselves
- so that I can follow your progress
- where you can ask questions (always at the bottom of the document) that I or any of you can answer.
