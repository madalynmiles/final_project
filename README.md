# Study Reveals That Middle-Agers May Be The *Highest Drug Users of All 

### *A 2012 study from the National Survey on Drug Use and Health from the Substance Abuse and Mental Health Data Archive reveals demographic breakdown of drug users and the drugs they used. 
###### *(no pun intended) 

##### By: Madalyn Miles  



Description of Data:

This data was retrieved from a fivethirtyeight dataset set called "Drug Use By Age", uploaded by Andrew Flowers. I was easily able to load the original .csv file from his Github page into a new google sheet to clean the data for the purposes I wanted to use if for, and interrogate it.

Cleaning the Data: 

Initially, this data had a lot of information that I decided not work on, so I ended up deleting it in order to paste it into a new data sheet and make it into tables. The median number of times people in a given age group used a given job was not something that I had time to analyze, so I removed it from my original .csv file to ensured that I could look at a clean dataset and analyze the columns I wanted to visualize as charts. 


Interrogating the Data:

* To find out which age group seems to be using drugs the most, I sorted the sample size column in descending order and was surprised to find that ages 35-39 won by a large margin.

![Chart of overall drug use by age](https://docs.google.com/spreadsheets/d/e/2PACX-1vTdXmIZb5FXP7sn-6MKcUoFPBHwpqloKLOpc8L5HajMO2RGyqJGAmseD6jX0CvG_7JWBNMgwwY8jCD3/pubchart?oid=1259785085&format=image)

*Drug types include: Alcohol, marijuana, pain reliever, tranquilizer, cocaine, crack, oxycontin, stimulant, hallucinogen, sedative, inhalant, meth, and heroin.
 
Seems the long workdays are hitting these middle-agers hard. Or maybe it's just a mid-life crisis. 

I then wondered: What drug is sending these empty nesters over the edge? To find out, I did a quick sort. 


Analysis: 

* Why do people ages 35-39 appear to be so drug happy? To my surprise, a quick sort reveleaed to me that the percentage of 35-39 year-olds who used **alcohol** in 2012 was nearly *eight* times as high as other drugs. 

<iframe title="Types of drugs 39 year-olds said they used in the past 12 months" aria-label="Bar Chart" id="datawrapper-chart-ngbFk" src="https://datawrapper.dwcdn.net/ngbFk/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="427"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


One reason for the high alcohol consumption relative to other drogs is that alcohol is legal, unlike meth and heroin for example. Alcohol is also one of the more socially accepted drugs. Individuals are more likely to report using alcohol at least in the past over a more taboo drug such as marijuana. 


* Another interesting thing the data shows a significant drop in drug use from the 35-39 to the 22-23 age group, almost by 60 percent. Indeed, low drug use percentages are seen in essentially all the age groups from age 12 to age 34. 
This is could represent younger families or young, working married couples, the former typically keeping drugs out of the house, the latter likely would not have much time for largely recreational drug-use. 


# Notes

Hiccups along the way:
As part of my personal cleaning process, I calculated total count of uses for every drug type for every age, but soon realized that the percentage would be just as effective to visualize on a chart, especially when comparing age-groups and usage. I ended up deleted these columns and calculations and going with the original percentages provided. Still, it provided valuable practice in visualizing how I wanted my data to be represented, as well as using and populatinng calculation formulas in google sheets. 

Limitations of the data: 
The data did not have any information on meth for the 65+ age group. 


