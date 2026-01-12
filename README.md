# Nightlife Geography and the Landscape of Urban-Noise
### 📖 [Read the Full Report Here](https://github.com/roni-pitkowsky/Nightlife-Geography-and-the-Landscape-of-Urban-Noise/blob/main/DATA%20716%2020251216%20Roni%20Pitkowsky%20Mini%20Thesis.pdf)
# 📌 Project Overview
Where and when does nightlife generate noise complaints in New York City? New York City is known as the city "that never sleeps": a defining feature of its identity is its nightlife. A common issue faced both by local government and by nightlife venues such as bars, nightclubs and concert venues is noise complaints. These complaints can limit venues’ ability to play music and can frustrate nearby residents, creating a lose-lose situation. It is therefore important to determine where complaints are happening and if they can be prevented, making neighbors happy and allowing nightlife, as well as the overarching economy, to flourish.

Previous research shows that urban noise links to things like building density and business clusters, and complaints spike on weekends when social activity is highest. But most studies haven’t looked specifically at nightlife venues, especially not across all five NYC boroughs at the census tract level. This study fills that gap by testing whether nightlife concentration predicts noise complaint frequency. I hypothesize there is a positive association between neighborhood nightlife density and resident noise complaints.

This study examined all 2,322 census tracts across New York City’s five boroughs using 2020 Census tract boundaries. Data was drawn three primary sources to examine the relationship between nightlife and noise complaints in New York City: 311 Service Requests from 2010 to Present (NYC Open Data, 2025), Current Liquor Authority Active Licenses (Open NY, 2025) and 2023 ACS 5-Year Estimates from (IPUMS NHGS; Mason et al., 2023).


# 📂 Datasets
The datasets used were provided by NYC Open Data and NY Open Data.<br/>
🔊 [311 Service Requests from 2020 to Present](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/data_preview)<br/>
🍻 [Current Liquor Authority Active Licenses](https://data.ny.gov/Economic-Development/Current-Liquor-Authority-Active-Licenses/9s3h-dpkz/about_data)<br/>
🗺️ [2020 NYC Census Tracts](https://data.cityofnewyork.us/City-Government/2020-Census-Tracts/63ge-mke6/about_data)

# 📈 Findings
While neighborhoods with more nightlife do experience higher complaint levels, supporting 
my initial hypothesis, the relationship is more nuanced than anticipated. The nonlinear pattern suggests 
potential saturation effects, while methodological insights reveal how statistical choices shape our 
understanding of urban phenomena. These findings point toward connect-sensitive approaches to urban 
noise management. With nightlife zones limiting impacts on constituent complaints.

<img width="3000" height="1800" alt="noise_complaints_saturation_plot" src="https://github.com/user-attachments/assets/e11acc5d-94b0-4954-a838-6d15799adaa1" />


# 🖥️ Tools & Technologies
- **R:** Performed data cleaning, transformation, and analysis.
