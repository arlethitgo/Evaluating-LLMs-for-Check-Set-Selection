## Task 1: humanitarian vs. not humanitarian.
We sampled from consolidated disaster events from CrisisMMD (Alam et al., 2018) dataset specifically from the following crisis events: Pakistan Earthquake 2013, California Earthquake 2014, Chile Earthquake 2014, India Floods 2014, Nepal Earthquake 2014, and Vanuatu Cyclone 2014. We randomly sampled 500 tweets for each disaster event.

## Task 2:  Humanitarian Aid Information Classification
Originally, we experimented with including the labels: other relevant information and not humanitarian, however, this seemed to be too challenging
for the LLM. The humanitarian aid information labels are as follows:
- Caution and advice: Reports of warnings issued or lifted, guidance and tips related
to the disaster;
- Infrastructure and Utility Damage: Reports of any type of damage to infrastructure
such as buildings, houses, roads, bridges, power lines, communication poles, or vehicles;
- Injured or dead people: Reports of injured or dead people due to the disaster;
- Rescue, volunteering, or donation effort: Reports of any type of rescue, volunteer ing, or donation efforts such as people being transported to safe places, people being
evacuated, people receiving medical aid or food, people in shelter facilities, donation
of money, or services, etc.;
- Sympathy and support: Tweets with prayers, thoughts, and emotional support
  
We sampled the test sets of the following crisis events: Canada Wildfires 2016, Cyclone Idai 2019, Greece Wildfires 2018, Mexico Earthquake 2017, Hurricane Matthew 2016, Hurricane Harvey 2017, Hurricane Maria 2017, Italy Earthquake 2016, Maryland Floods 2018, and Sri Lanka Floods 2017. We randomly sampled 300 tweets for each disaster even
