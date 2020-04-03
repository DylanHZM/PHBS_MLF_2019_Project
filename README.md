# Subsequently Released or Not? A Binary Prediction of Coronavirus in South Korea 
(PHBS_MLF_2019_Project / [Course Link](https://github.com/PHBS/MLF))  

## Members 
| Name                                           | SID        |
|---                                             |---         |
|[Jingwei Gao](https://github.com/LobbyBoy-Dray) | 1801213126 |
|[Simon SHEN](https://github.com/Simon9511)      | 1801212832 |
|[Yingjie Jiang](https://github.com/Jason422)    | 1901212596 |
|[Rongxin Ouyang](https://github.com/oyrx)       | 1801213136 |


## Project Description
| Project  |  Details |
|---|---|
| **Goal**  |  To predict a binary result of each patient wether he/she would be released in a certain time period *(threshold TBD here)*. |
| **Data**  |  [COVID-19 in South Korea](https://www.kaggle.com/kimjihoo/coronavirusdataset)  on Kaggle|
| **Data Description**  |  This dataset depicts about COVID-19 in South Korea, including cases, patients, patient routes, regions, search trends, seaoul floatingg, time, time/age, time/gender, and weather. Figures in this dataset have been structured from public materials of KCDC and local governments.|  
  
**Data Details**  *  
patients.csv:
- `patient_id` the ID of the patient  
- `global_numthe` number given by KCDC  
- `sexthe` sex of the patient  
- `birth_year` the birth year of the patient  
- `age` theage of the patient  
- `country` the country of the patient  
- `province` the province of the patient  
- `city` the city of the patient  
- `disease` TRUE: underlying disease / FALSE: no disease  
- `infection_case` the case of infection  
- `infection_order` the order of infection  
- `infected_by` the ID of who infected the patient  
- `contact_number` the number of contacts with people  
- `symptom_onset_date` the date of symptom onset  
- `confirmed_date` the date of being confirmed  
- `released_date` the date of being released  
- `deceased_date` the date of being deceased  
- `state` isolated / released / deceased  
  
...  

**Features for prediction will also be engineered or extracted from other files in the same dataset:*  ***(TBD)***
  

## (TBD)
(TBD)


## License and Aknowledgements
This project is under `BY-NC-SA` – [Attribution-NonCommercial-ShareAlike](https://github.com/idleberg/Creative-Commons-Markdown/blob/master/4.0/by-nc-sa.markdown).  
  
Thanks to data providers:
- Project Manager: JoongKun Lee (absent)
- Project Leader: ByeongUk Yu / MuHwan Kim / SeoJin Jang / SeongHan Ryoo / YeonJun In
- Project Engineer: BoYoung Song / DongHwan Jang / Jimi Kim / JuHwan Park (retired) / KyeongWook Jang / MinSeok Jung / SangWook Park / TaeHyeong Park / WanSik Choi / Won Hwang (retired) / WonCheol Lee / YouNa Jung / Logo Designer / RinChong Kim
- Project Advisor: Jihoo Kim
