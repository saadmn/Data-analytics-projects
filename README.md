# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The dataset contains records of Ford GoBike service during 2018 in San Francisco, each row is a trip from station A to station B, its start time and its end time, the type of the user (subscriber or customer), its birth year, and other details.
The source of the data is Ford itself through AWS CSV links for each month of 2018 so, in order to get the whole data in one place, I had to create a folder to store the 12 CSVs and then concat them in one table.
The dataset was pretty much clean, I just change some column types and perform some data augmenting in order to get more information for better visualization.

## Summary of Findings

> During my univariable performing, I found that most rides are made from Monday to Friday at 8 pm and 5 pm, so I started to get suspicious if the users are using their the GoBike as a medium to go to their jobs, so I have to dig more during my bivariable and multivariable analysis which leads to finding that subscribers are more predicables then casual customer and in fact, they have some sort of a routine at using the service, to their age and average duration of each trip confirm this claim which drives me to conclude that most subscribers are using the service to get to their jobs.

## Key Insights for Presentation

> > For the presentation, I focus just on studying my hypothesis that I found in the univariable part of the analysis, so the age, user type, and duration of the trip were the most variables I did work with, for the aim of consistent storytelling and not lead to confusing the reader.