# AIRCRAFT PURCHASE RECOMMENDATIONS

## Project overview
The primary aim of this project is to come up with a system that accurately classifies whether an aircraft is high-risk or low-risk based on the model and brand's history of accidents and incidents. 
This project will help come up with actionable insights that will accurately advise and guide the head of the new aviation division to make accurate and data-driven decisions on the purchase and operation of airplanes for commercial and private enterprises as the company ventures into this new business endeavor. 

### Project links
To view an interactive visualization of the project, use this [link](https://public.tableau.com/views/AircraftPurchaseRecommendations/Aircraftpurchaserecommendations?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

For a simplified version, the presentation will serve you, to access it use this [link](https://1drv.ms/p/c/9fb0e9e462d93906/EaN9nBCmFZtGifZ0iCipkx4Blo7dZvK-YKd2KBSa6Twxlg?e=sjNwsY). 

## Business understanding
### Business problem
According to aviation and plane crash statistics, the odds of an airplane crashing are approximately 0.000001%. Out of 816,545,929, the chance of being killed in a plane crash is 1.
Most factors that contribute to airplane crashes are normally out of human control, such as weather conditions, however, factors that play significant roles in accident risks are aircraft model, maintenance, and oversight, all things that are humanly possible to control.

Making purchases, especially when a company ventures into a business they have no expertise, can prove to be daunting. This being the foundational phase of a business, having expert advice significantly increases the chances of having a successful business. However, as much as human knowledge is valuable, it is also subjective and prone to biases. There is a pressing need to have a more scientific and evidence-based approach to help aviation businesses make informed decisions when making purchases.

### Business questions
1. Which aircraft is the lowest risk for the company to start this new business endeavor?
2. What actionable insights can I offer the head of the new aviation division to help decide which aircraft to purchase?

### Stakeholders
1. Head of the new aviation division: The head of the new aviation division will use the recommendations to guide his decisions on purchasing new business enterprises for commercial and private use.
2. Aviation companies: Companies wanting to upgrade will use this project to guide their upgrades, as well as their maintenance and oversight

## Data understanding
### Data source
In this repository, under the file path `Data,` there are 2 CSV files containing information about aviation accidents and incidents documented by the USA National Transportation Safety Board (NTSB) between 1948 and 2022.

The NTSB aviation accident database, `AviationData.csv`, contains information from 1948 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters.
`USState_Codes.csv` file contains information about the US states and their abbreviations.

This dataset is most suitable for this particular project as it contains information from as far back as 1948 and as recent as 2022, which gives us a wide range of information to understand what works and what does not in the aviation world.

### Data description
The dataset contains structured data in 31 columns and 88889 rows. Out of 31 columns, only 4 columns contain the full 88889 records; the rest are either missing or have as few as a hundred plus records to as many as seven thousand records.
The dataset has 5 columns containing the `float64` data type and 26 columns containing the `object` data type, and contains 938 duplicate records.

## Recommendations
### Models and makes
After thorough analysis of the `Filtered_Aviation_data` on Aviation accidents databases and synopses, I strongly recommend that the head of the new aviation division consider purchasing the 'Sportsman', 'Lancair O-200', '205A', 'PARSONS STILES GYRO', 'T210 - H', 'L-18C', 'BATHTUB', 'CGS HAWK ARROW II', 'PA-28-140B', 'TopDog Ultralight', 'DAVIS DA-2A', 'SKY RAIDER 1', 'High Tow', 'AVID C AEROBAT', 'Lancair 360A', '400', '112', 'PA-12', '108-2', 'FBA 2C2', 'PA 24-250', 'D55', '182C', 'Hawker 800XP', 'PA-32-301', 'C46', '210M', 'Mystere Falcon 900', 'NA-265-80', 'G21models', 'A119', 'DA 20-C1', 'A 1', '152', 'SA319B Alouette III', 'PA 18', 'CH-54A', 'TU206G', 'MT-7-235', 'A4L', 'P.68', 'PA-32-300', 'S2T-T65', '500', '47G' models. These models have demonstrated the lowest operational risk among thousands of comparable aircraft, showing exceptional reliability and minimal accident rates even after the industry's advancements and significant strides, as well as advanced technology.

Also, I recommend purchasing models from 'Lantz', 'Girard', 'Honda Aircraft', 'Sea & Sky Inc Dba Krucker Acft', 'Steven Hardie', 'Wright B Flyer Inc', 'Stuhlmiller Robert', 'Raytheon Company', 'Caldwell', 'Maxair Drifter', 'Texas Helicopter Corporation', 'Trusty', 'Motley Gary W', 'Martin/Harris' and 'Michael Burton' aircraft manufactures. These makes have been proven to have the lowest risks based on their low accident rates.

Having identified these makes and models from a sea of records, I strongly believe that safety records, combined with modern and advanced flight systems, make the above models and makes the ideal choices for companies starting their aviation journey. These models and makes will also help maximize operations, positioning the company for growth.  

![Result 1](https://github.com/user-attachments/assets/e12c353f-5d04-4161-95b0-07d999617392)

### Commercial and private aircraft
The project at hand looks to identify low-risk aircraft for commercial and private use. After carefully analyzing the data, I have identified aircraft that I strongly recommend the head of the new aviation division consider using for the two intended purposes. I recommend the uses of the 'Sportsman', 'Lancair O-200', '205A', 'PARSONS STILES GYRO', 'T210 - H', 'L-18C', 'BATHTUB', 'CGS HAWK ARROW II', 'PA-28-140B', 'TopDog Ultralight', 'DAVIS DA-2A', 'SKY RAIDER 1', 'High Tow', 'AVID C AEROBAT' and 'Lancair 360A' models for Private use. 

The models above were used for personal flights. Personal flight refers to a flight operated for private or individual purposes, rather than for commercial or business travel. This can include leisure travel, flying for recreation, or even flights related to hobbies or personal events. It is based on the meaning and the low-risk aspect that I recommend the aircraft above for this purpose.

For commercial use, I recommend the use of the 'A119', 'DA 20-C1', 'A 1', '152', 'SA319B Alouette III', 'PA 18', 'CH-54A', 'TU206G', 'MT-7-235', 'A4L', 'P.68', 'PA-32-300', 'S2T-T65', '500' and '47G' models.  As the name suggests, these models were built and designed for that purpose.

The last recommendation on the purpose of aircraft, I recommend the use of the '400', '112', 'PA-12', '108-2', 'FBA 2C2', 'PA 24-250', 'D55', '182C', 'Hawker 800XP', 'PA-32-301', 'C46', '210M', 'Mystere Falcon 900', 'NA-265-80', 'G21models' models for both of the intended purposes. These aircraft can serve either the purposes of commercial or private flights. 

These models, when used for the specified purposes, could maximize operations to grow in the increasingly competitive market.

![Result 1 1](https://github.com/user-attachments/assets/a5f5e6ba-5174-4eb4-955b-4d336ba284ee)

### Engine type
A good purchase goes hand in hand with maintenance, as much as purchasing a low risk aircraft looks at the safety aspect of the aircraft, it also focuses on costs and longterm suitability. It is at the back of these aspects that I strongly recommend Long Range 'LR' and electric engines to be considered as the engine types for the models to be purchased.

According to my analysis, the two-engine recommended models have accident rates of less than 5 in 22 years. This proves the engines' suitability for the long-term operations, eradicating the need for costly maintenance repairs that would otherwise dig holes into the company's pockets.

![Result 3](https://github.com/user-attachments/assets/64b4f657-074e-4150-819c-b4f1bedf7825)


## Conclusion
#### Overview
The project was meant to come up with a system that accurately classifies whether an aircraft is high-risk or low-risk based on the model and brand's history of accidents and incidents and identify and recommend low-risk aircraft to help and guide the head of the new aviation division to purchase aircraft for the company's new business endeavor.

#### Key Findings
After the processes of Explorative Data Analysis and data cleaning, I identified over 40 aircraft models, 15 makes and 2 engine types that proved to be low-risk and recommended them to the head of the new aviation division, and specified the use of each and every model for the purchase of aircraft for commercial and private use. 

#### Impact
The project wll help the head of the new aviation division prioritize aircraft with the best safety records, reducing the likelihood of accidents or incidents, which in turn will boost passenger confidence. It will also help reduce financial costs, a low-risk aircraft means less unscheduled repairs and lower insuarance costs, which will help the company save money.

For companies starting up in the business, this project will help them make data-driven decisions, which will eliminate the need for costly expert advisors who may have their agendas. Many times, experts already have companies that they recommend to their clients, to whom they are biased towards; this project aims to eradicate any biases and generate recommendations that will be evidence-based.

Additionally, it will enhance their business outcomes. High-risk aircraft can prove to be costly, when airline plane crashes, the immediate business impact involves significant financial losses, reputational damage, and potential long-term operational challenges. Having accurate information on low risk models help them avert these crises in the future.

# END/
