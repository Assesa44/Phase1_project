# AIRCRAFT PURCHASE RECOMMENDATION

## Project overview
The primary aim of this project is to come up with a system that accurately classifies whether an aircraft is high-risk or low-risk based on the model and brand's history of accidents and incidents. 
This project will help come up with actionable insights that will accurately advise and guide the head of the new aviation division to make accurate and data-driven decisions on the purchase and operation of airplanes for commercial and private enterprises as the company ventures into this new business endeavor. 

## Business understanding
### Business problem
According to aviation and plane crash statistics, the odds of an airplane crashing is approximately 0.000001%. Out of 816,545,929, the chance of being killed in a plane crash is 1.
Most factors that contribute to airplane crashes are normally out of human control such as weather conditions, however, factors that play significant roles in accident risks are aircraft model, maintenance and oversight, all things that are humanly possible to control.

Making purchases, especially when a company ventures into business they have no expertise in, can prove to be daunting. This being the foundational phase of a business, having expert advice significantly increases the chances of having a successful business. However, as much as human knowledge is valuable, it is also subjective and prone to biases. There is pressing need to have a more scientific and evidence-based approach to help aviation businesses make informed decisions when making purchases.

### Business questions
1. Which aircraft are the lowest risk for the company to start this new business endeavor?
2. What actionable insights can I offer the head of the new aviation division to help decide which aircraft to purchase?

### Stakeholders
1. Head of the new aviation division: the head of the new aviation division will use the recommendations to guide his decisions on the purchases for the new business enterprises for commercial and private uses.
2. Aviation companies: companies wanting to upgrade will use this project to guide their upgrades as well as their maintenance and oversights

## Data understanding
### Data source
In this repository, under the file path `Data` there are 2 CSV files containing information about aviation accidents and incidents that happened between 1948 and 2022 documented by the USA National Transport Safety Board (NTSB).

The NTSB aviation accident database, `AviationData.csv`, contains information from 1948 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters.
`USState_Codes.csv` file contains information about the US states and their abbreviations.

This dataset is most suitable for this particular project as it contains information from as far back as 1948 and as recent as 2022, which gives us a wide range of information to understand what works and what does not in the aviation world.

### Data description
The dataset contains structured data that has been put in 31 columns and 88889 rows. Out of 31 columns, only 4 columns contain the full 88889 records, the rest are either missing from as low as a hundred plus records to as high as seven thousand records.
The dataset has 5 columns containing the `float64` data type and 26 columns containing the `object` data type and contains 938 duplicate records.

Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

