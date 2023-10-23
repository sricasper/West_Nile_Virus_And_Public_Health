# West_Nile_Virus_And_Public_Health
Engaging in data wrangling activities and employing statistical analysis techniques to develop models assessing the probability of detecting West Nile Virus at specific timeframes and locations in the city of Chicago

### Dataset

Mosquito_data dataset will be used in this report. The dataset contains information about West Nile Virus (WNV) which is a viral illness largely spread by mosquitos. The disease is transmitted to a person when an infected mosquito bites them. Moreover, the dataset also shows tracking data of mosquito populations and WNV prevalence using a series of traps that were placed around the city by The City of Chicago, Illinois from 2008 to 2019.

#### Data Dictionary

- <b>Year</b>: Year that the WNV test is performed (int64)
- <b>Week</b>: Week that the WNV test is performed (int64)
- <b>Address Block</b>: Address of the location of trap (string)
- <b>Block</b>: Block number of address (int64)
- <b>Trap</b>: Id of the trap (string)
- <b>Trap type</b>: Type of trap (string)
- <b>Date</b>: Date and time that the WNV test is performed (string)
- <b>Mosquito number</b>: Number of mosquitoes caught in this trap (int64)
- <b>Mosquito ID</b>: Id for Mosquito species (string)
- <b>WNV Present</b>: Whether West Nile Virus was present in these mosquitos (string)
- <b>Species</b>: Mosquito species (string)
- <b>Lat</b>: Latitude of trap (float64)
- <b>Lon</b>: Longitude of trap (float64)

#### Field of Interest

Explore the relationships within the dataset, such as mosquito number, species, WNV prevalence, and trap type.
