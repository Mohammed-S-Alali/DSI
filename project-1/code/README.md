

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Local Traffic, Statistical Summaries and Inference

### Problem Statment

<p style="text-align:justify"> Traffic accidents in the Kingdom of Saudi Arabia have been increased last years. Many people lost their health and cars. Also, the hospitals have overloaded due to emergency cases. The economy will be affected in the long term if accidents are ongoing. The aim of this project is to investigate the reasons for a traffic accident with driving licenses to provide highly efficient recommendations in order to reduce injuries and casualties on the road. </p>

---

### Executive Summary

<p style="text-align:justify">This project focuses on data of traffic accidents with driving licenses in the Kingdom of Saudi Arabia, which provides the number of traffic accidents and issued driving licenses per region yearly. Currently, traffic accidents and driving licenses have been increased in the last years. As a result, the General Department of Traffic has lost little control over traffic accidents. So, the objective of this project is to enhance control. The project conducts on data analyzing process and data.</p>
Exploratory data analysis, descriptive and inferential statistics produce the findings:
<ol>
    <li>The top 3 regions on traffic accidents in 2017 are Makkah(%31.6), Riyadh (%21.69) and Eastern Region (%17.68).</li>
    <li>The highest region on issued driving licenses in 2017 is Riyadh by 495,307 licenses (%53.36).</li>
    <li>The top 3 region on number of casualties in 2016 are Makkah (31%), Eastern Region (%12.73) and Riyadh (%11.95).</li>
    <li>The traffic accidents and issued driving licenses are postive skewed due to certain regions are huge compared the rest regions.</li>
</ol>
<p style="text-align:justify">&nbsp;&nbsp;&nbsp;Based on the findings, it is recommended that focuses on the infrastructure of roads and emphasizes the traffic rules on main roads. Also, adds more restrictions on issued driving licenses. Those recommendations will save people from traffic accidents and encourage safe driving.</p>

---

### Data Dictionary

#### Traffic Accidents dataset <a href="https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/export/?disjunctive.region&disjunctive.indicator&sort=time_period">source</a>

|Feature|Type|Dataset|Description|
|--|--|--|--|
|Year|int|Traffic_Accidents|Year of traffic accident.|
|Region|object|Traffic_Accidents|Region of traffic accident in Saudi Arabia.|
|Indicator|object|Traffic_Accidents|Indicate the type of traffic accident.|
|Count|int|Traffic_Accidents|Number of each traffic accident type.|
|geo_point_2d|object|Traffic_Accidents|The geolocation of region in Saudi Arabia.|
|x|float|Traffic_Accidents|The latitude of geolocation|
|y|float|Traffic_Accidents|The longitude of geolocation|

<br>

#### Driving Licenses dataset <a href="https://datasource.kapsarc.org/explore/dataset/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008/information/?disjunctive.administritive_area&sort=time_period&location=5,24.37495,45.08024&basemap=jawg.streets">source</a>

|Feature|Type|Dataset|Description|
|--|--|--|--|
|Year|int|Driving_Licenses|Year of issuance driving licenses.|
|Region|object|Driving_Licenses|Issued Region of driving licenses in Saudi Arabia.|
|Driving Licenses|int|Driving_Licenses|Number of issuanced driving licenses.|
|geo_point_2d|object|Driving_Licenses|The geolocation of region in Saudi Arabia.|
|x|float|Driving_Licenses|The latitude of geolocation|
|y|float|Driving_Licenses|The longitude of geolocation|

---

### Conclusions/Recommendations

<p style="text-align:justify">The diversity of life in KSA leads the community to explore themself like getting jobs and tourism. The population growth appears in driving licenses. Makkah, Riyadh and Eastern Region are top 3 among many years in issued driving licenses. So, it is related to accidents which are more drivers more accidents probably. The findings in the traffic accidents dataset prove the previous fact since the top 3 regions in driving licenses are the same in traffic accidents. The recommendations are focusing on the infrastructure of roads and emphasizing on the drivers to follow traffic rules on main roads to reduce the opportunity of accidents and traffic jams. Also, add more restrictions on using mobile during driving and issued new driving licenses. Those recommendations will save people from traffic accidents and encourage safe driving.</p>