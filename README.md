# AIRCRAFT PURCHASE RECOMMENDATIONS

## Project overview
The primary aim of this project is to come up with a system that accurately classifies whether an aircraft is high-risk or low-risk based on the model and brand's history of accidents and incidents as documented in [kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses). 
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

### Exploratory data analysis
 Digging deeper into the dataset, I looked at each column closely, visualizing them to understand their contents in depth, and identifying the relationships between the columns. This process helped me identify the most relevant columns for the project. I used bargraphs for individual columns, to compare the contents within and also used correlation to identify the relationship between the columns. 

## Data analysis
After thorough analysis and increased attention to the details, I decided to use the following columns for my analysis;

1. `Model` - As the project is about identifying aircraft to purchase, this was the most relevant column. The column contains information about the models of the aircraft that have been involved in accidents, helping me pinpoint the exact aircraft to purchase, providing insight into what models are prone to accidents and which ones are not.

2. `Make` - Next to `Model`, this was the other important column. This column contains information about which models belong to which make. Several makes have the same types of models, which helped identify which make the company should purchase a model from.

3. `Engine.Type` - This column contains information about the kind of engines the aircraft had. It is important for purposes of maintenance, as it will help identify what engines are most favourable to have on an aircraft.

4. `Year` - This contains information about what year an accident took place in. This will help monitor aircraft advancement through the years. It is important to look at the years as they provide another perspective other than `Model` and `Make`. Through the years, aircraft have gone through advancements, and it is important to look at that as well, instead of making a decision based on only one aspect.

5. `Purpose.of.flight` - To find out the use of an aircraft, we need to know its purpose. This column contains information about the purpose of the aircraft, It is important because it will help identify if the aircraft is for commercial or private use.

## Recommendations
### Models and makes
After thorough analysis of the `Filtered_Aviation_data` on Aviation accidents databases and synopses, I strongly recommend that the head of the new aviation division consider purchasing the 'MBB BK 117 C-2', 'UH 1H', '500D', 'H500D', '207', 'HAWKER', 'L-39', 'Prescott Pusher', 'M20E', '2T 1A', 'ZENAIR CH 701 SP', 'CRICKET MC12', 'Super Cub Replica', 'DH-82-C', and 'Navion H' models. These models have demonstrated the lowest operational risk among thousands of comparable aircraft, showing exceptional reliability and minimal accident rates even after the industry's advancements and significant strides, as well as advanced technology.

Also, I recommend that the head of the new avation division consider purchasing models from 'Brinkerhuff Gerald G', 'Backovich George C', 'Kolb Aircraft Co', 'Roberts Bruce W', 'Purvis', 'Cano Dave', 'Zivko', and 'Terrence A. Sack' aircraft manufactures. These makes have been proven to have the lowest risks based on their low accident rates.

Having identified these makes and models from a sea of records, I strongly believe that safety records, combined with modern and advanced flight systems, make the above models and makes the ideal choices for companies starting their aviation journey. These models and makes will also help maximize operations, positioning the company for growth.

![models 1](https://github.com/user-attachments/assets/82ced35a-6101-4524-976c-0072cbf53d28)

### Commercial and private aircraft
The project at hand looks to identify low-risk aircraft for commercial and private use. After carefully analyzing the data, I have identified aircraft that I strongly recommend the head of the new aviation division consider using for the two intended purposes. I recommend the use of the 'ZENAIR CH 701 SP', 'CRICKET MC12', 'Super Cub Replica', 'DH-82-C', and 'Navion H' models for Private use. 

The models above were used for personal flights. Personal flight refers to a flight operated for private or individual purposes, rather than for commercial or business travel. This can include leisure travel, flying for recreation, or even flights related to hobbies or personal events. It is based on the meaning and the low-risk aspect that I recommend the aircraft above for this purpose.

For commercial use, I recommend the use of the 'MBB BK 117 C-2', 'UH 1H', '500D', 'H500D', and '207' models.  As the name suggests, these models were built and designed for that purpose.

The last recommendation on the purpose of aircraft, I recommend the use of the 'HAWKER', 'L-39', 'Prescott Pusher', 'M20E', and '2T 1A' models for both of the intended purposes. These aircraft can serve either the purposes of commercial or private flights. 

These models, when used for the specified purposes, could maximize operations to grow in the increasingly competitive market.

![models](https://github.com/user-attachments/assets/6f65cb7a-cdad-4676-8c0c-27d6cb245a51)

***Disclaimer*** It is important to note that these recommendations are just a handful of the low-risk models and make. To find more aircraft and make that would suit your budget, the head of the new aviation could use [tableau visualizations](https://public.tableau.com/views/AircraftPurchaseRecommendations/Aircraftpurchaserecommendations?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) to find aircraft that match the company's budget.

### Engine type
A good purchase goes hand in hand with maintenance, as much as purchasing a low risk aircraft looks at the safety aspect of the aircraft, it also focuses on costs and longterm suitability. It is at the back of these aspects that I strongly recommend Long Range 'LR' and electric engines to be considered as the engine types for the models to be purchased.

According to my analysis, the two-engine recommended models have accident rates of less than 5 in 22 years. This proves the engines' suitability for the long-term operations, eradicating the need for costly maintenance repairs that would otherwise dig holes into the company's pockets.

![Result 3](https://github.com/user-attachments/assets/64b4f657-074e-4150-819c-b4f1bedf7825)


## Conclusion
#### Overview
The project was meant to come up with a system that accurately classifies whether an aircraft is high-risk or low-risk based on the model and brand's history of accidents and incidents and identify and recommend low-risk aircraft to help and guide the head of the new aviation division to purchase aircraft for the company's new business endeavor.

#### Key Findings
After the processes of Explorative Data Analysis and data cleaning, I identified over 15 aircraft models, 10 makes and 2 engine types that proved to be low-risk and recommended them to the head of the new aviation division, and specified the use of each and every model for the purchase of aircraft for commercial and private use. 

#### Impact
The project wll help the head of the new aviation division prioritize aircraft with the best safety records, reducing the likelihood of accidents or incidents, which in turn will boost passenger confidence. It will also help reduce financial costs, a low-risk aircraft means less unscheduled repairs and lower insuarance costs, which will help the company save money.

For companies starting up in the business, this project will help them make data-driven decisions, which will eliminate the need for costly expert advisors who may have their agendas. Many times, experts already have companies that they recommend to their clients, to whom they are biased towards; this project aims to eradicate any biases and generate recommendations that will be evidence-based.

Additionally, it will enhance their business outcomes. High-risk aircraft can prove to be costly, when airline plane crashes, the immediate business impact involves significant financial losses, reputational damage, and potential long-term operational challenges. Having accurate information on low risk models help them avert these crises in the future.

# END/
