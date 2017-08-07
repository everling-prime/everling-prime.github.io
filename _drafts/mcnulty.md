---
published: false
---
# Nerdiness Quantified
## Patterns in aggregrate responses to the Nerdy Personality Assessment Scale

---

## Introduction

How do we collectively understand the concept of "nerdiness"? Are there particular personality types that are "nerdy"? Which personalities are proudest to call themselves nerds? Are there components of our collective conception of nerdiness that are rooted in autistic characteristics?

This project aims to use quantitative approaches to tackle these qualitative questions. 

The [Nerdy Personality Assessment Scale](http://personality-testing.info/tests/NPAS/) is a survey freely available online that aims to quantify nerdiness. 

> The Nerdy Personality Attributes Scale was developed as a project to quantify what "nerdiness" is. Nerd is a common social label in English, although there is no set list of criteria. The NPAS was developed by surveying a very large pool of personality attributes to see which ones correlated with self reported nerd status, and combining them all into a scale. The NPAS can give an estimate of how much a respondent's personality is similar to the average for those who identify as nerds versus those who do not.


**Here is the entire NPAS. Feel free to score yourself!**  
Procedure: The NPAS has 26 questions. In each questions you must rate how much you agree with a given statement on a five point scale where 1=Disagree, 3=Neutral and 5=Agree.

1. I sometimes prefer fictional people to real ones.					
1. I prefer academic success to social success.					
1. My appearance is not as important as my intelligence.					
1. I gravitate towards introspection.					
1. I am interested in science.					
1. I care about super heroes.					
1. I like science fiction.					
1. I spend recreational time researching topics others might find dry or overly rigorous.			
1. I get excited about my ideas and research.					
1. I like to play RPGs. (Ex. D&D)					
1. I collect books.					
1. I am a strange person.					
1. I would rather read a book than go to a party.					
1. I love to read challenging material.					
1. I spend more time at the library than any other public place.					
1. I would describe my smarts as bookish.					
1. I like to read technology news reports.					
1. I am more comfortable interacting online than in person.					
1. I was in advanced classes.					
1. I watch science related shows.					
1. I was a very odd child.					
1. I am more comfortable with my hobbies than I am with other people.					
1. I have started writing a novel.					
1. I can be socially awkward at times.					
1. I enjoy learning more than I need to.					
1. I have played a lot of video games.

Generally speaking, the higher your total, the more you align with statements from people who call themselves nerdy.

In addition the NPAS questions above, this site also administers an optional ten-item personality test (TIPI) based on the Big Five model of personality. This test yields a value for each of the following traits of the taker (the "big five traits"): Openness to Experience (O), Conscientiousness (C), Extraversion (E), Agreeableness (A), Neuroticism (N).  

collected various demographic variables:

* Age
* etc.


[Personality Testing](http://personality-testing.info/) offers an anonymized dataset of approximately 1500 responses to the survey.

Data Cleaning and Transforms:

* Exclude rows that do not have complete data for: NPAS questions, TIPI personality inventory, and basic demographics.
* Tranform categorical variables to "dummy" binary variables. 
* Calculate Big 5 personality scores based on TIPI responses.
* 
