---
layout: post
title:  "Tool for analysing costs of different green trucking technologies"
date:   2023-01-28 10:00:00

---


Dear eMobility & trucking enthusiasts, are you interested in comparing different green trucking technologies and understanding drivers of costs? 
  
I built a total cost of ownership (TCO) tool based on the study by Transport & Environment (T&E) ['How to decarbonize long-haul trucking in Germany'](https://www.transportenvironment.org/wp-content/uploads/2021/07/2021_04_TE_how_to_decarbonise_long_haul_trucking_in_Germany_final.pdf){:target="_blank"}  🚚🔋⚡? The model is parameterized for 40 t semitrucks, but can easily be changed to other classes.
  
Can be found [**here**](https://lnkd.in/efJxReJn){:target="_blank"} (works best on desktop/tablet). 

The tool gives the opportunity to play around with cost drivers (e.g. what difference does an increase of CO2 price from 25 to 100 €/t make on TCO).

![screenshot of tco webtool](/assets/img/content/green-trucking/screenshot-tco-tool.png)


Some insights: 
  
- Battery electric trucks have especially in the midterm the upper hand, being cheaper today than other technologies including diesel with the current german KsNI subsidy (80% of invest). Cost parity of battery electric trucks without subsidies in comparison with diesels can be reached somewhere in the 2025s. 
- Next to KsNI subsidy, toll exemptions are the biggest positive cost driver for green trucking technologies, as toll fees make up normally more than 20 % of TCO of diesel trucks. 
- When comparing fuel cell and battery electric trucks on a European level, because of high electricity prices in Germany and imported hydrogen price staying the same across Europe, battery electric trucks should have a higher relative edge in other European countries compared to Germany. 
- fuel cell electric trucks green hydrogen price and vehicle cost are in comparison to battery electric trucks cost drivers relatively uncertain, as large scale green hydrogen nor (passenger) vehicle supply chains exist.

For Techies: I built the app with the awesome pythonic tool [streamlit](htttps://streamlit.io){:target="_blank"}. Source code can be found on [Github](https://lnkd.in/eYMYUVX2){:target="_blank"}.
Maybe I will do a small follow-up post on the streamlit.
  
Feedback very welcome, but as I built this in my freetime bugs and errors are probably in abundance ;)