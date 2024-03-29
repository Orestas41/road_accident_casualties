<h1 align='center'>Road Accident Casualties</h1>
<h3 align='center'>Orestas Dulinskas</h3>
<h4 align='center'>January 2024</h4>

## Background

Road accidents continue to pose a significant threat to public safety globally, causing injuries, fatalities, and economic losses. Analyzing road accident casualty records can provide invaluable insights into the factors contributing to these incidents. The dataset under consideration encompasses detailed information about accident severity, environmental conditions, geographical locations, and vehicle-related variables recorded throughout England and Wales from 2019 to 2022. Understanding the relationships and patterns within this dataset offers an opportunity to identify key risk factors and develop targeted strategies to mitigate road accidents' impact.

## Objective
The primary objective of this data science project is to leverage machine learning and statistical analysis techniques to predict accident severity. By developing predictive model and conducting exploratory data analysis, the project aims to understand how various factors like weather conditions, road types, lighting, and vehicle characteristics impact accident severity. Geospatial analysis will be employed to pinpoint high-risk areas.

## Data

The dataset, sourced from Kaggle (willianoliveiragibin/road-accident-casualties), comprises comprehensive road accident casualty records throughout England and Wales from 2019 to 2022, offering a rich repository of information crucial for understanding and mitigating road accidents. It encompasses various features that intricately detail the circumstances surrounding each incident. The key features within this dataset include:

* Accident Severity: Indicates the severity level of each accident, categorizing them as slight, serious, or fatal.
* Light Conditions: Describes the lighting status during the accident, distinguishing between daylight, darkness with street lights, darkness without street lights, and other conditions.
* Accident Date: Specifies the date when the accident occurred.
* District Area: Indicates the geographical area or district where the accident occurred.
* Latitude & Longitude: Provide the precise geographical coordinates of the accident location.
* Number of Vehicles: Records the count of vehicles involved in each accident.
* Number of Casualties: Indicates the number of individuals affected by the accident.
* Road Surface Conditions: Describes the state of the road surface during the accident, such as dry, wet, snow, ice, etc.
* Road Type: Specifies the type of road where the accident occurred, whether single carriageway, dual carriageway, or other designations.
* Urban or Rural Area: Indicates whether the accident took place in an urban or rural setting.
* Vehicle Type: Records the types of vehicles involved, including cars, vans, motorcycles, etc.
* Weather Conditions: Describes the prevailing weather conditions at the time of the accident, such as rain, fog, clear skies, etc.

## EDA Summary

Most of the accidents result in slight injuries, while serious and fatal accidents are less common. The number of accidents has been decreasing from 2019 to 2023, with the lowest rates in February and Monday. The highest rates of accidents occur in October and November, and on Saturdays. Most of the accidents happen in urban areas, especially in London and the mid-lands, where major cities are located. However, fatal accidents are more likely to happen in rural areas, especially on roundabouts and slip roads. The most common type of road where accidents happen is single or dual carriageway, but many accidents have no road type specified. The most common type of vehicle involved in accidents is car, but serious and fatal accidents also involve vans, minibuses, agricultural vehicles, and bikes. Most of the accidents involve one or two vehicles, and one or two casualties. However, serious accidents tend to involve more vehicles and casualties, while fatal accidents can involve either one or more than six casualties. The most common light condition where accidents happen is daylight, but serious and fatal accidents also happen in darkness, with or without lights. The most common weather condition where accidents happen is fine with no wind, but many serious and fatal accidents have no weather condition specified. Some of the fatal accidents also involve snowing with high winds. These patterns and factors can help to identify the risk factors and preventive measures for road safety.

## Model Training Summary

In the model training phase of the project, a comprehensive dataset consisting of various pertinent features such as light conditions, urban or rural area classification, road surface conditions, road type, weather conditions, vehicle types, day of the week, month, and number of vehicles involved was utilized. The aim was to predict accident severity levels. The dataset was preprocessed meticulously, addressing missing values, encoding categorical variables, and handling outliers to ensure data quality. A Decision Tree algorithm was chosen for its interpretability and effectiveness in handling categorical data. The model was trained on a subset of the dataset and validated on another to assess its performance. The results achieved were notably promising, with an overall accuracy of 99% and high precision and recall scores across different severity levels. Specifically, the model exhibited remarkable precision rates of 98% for Slight severity, 95% for Severe severity, and 100% for Fatal severity, along with robust recall rates, particularly identifying all instances of Severe severity and most instances of Fatal severity accurately. These outcomes indicate the model's proficiency in distinguishing between different levels of accident severity based on the provided features, providing a solid foundation for further analysis and potential deployment for real-world applications in accident prevention and response strategies.