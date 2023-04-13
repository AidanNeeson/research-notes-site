---
title: "Experiment"
date: 2023-04-13T14:39:56-04:00
draft: False
---

# Modeling Standard Young Tableaux Using Python

I initally created the means to model Young Tableaux using the Python programming language. Once this was done, I added the capability to test these tableaux to check if they are standard or not. Once this was completed, I was able to fully implement my random assignment experiment. I set up 50 trials that generated 100,000 random tableaux of shape (5,4,1) per trial, randomly assigning values to create each one. I then kept track of how many standard young tableau were created in each trial, averaged the values and displayed them in a chart for data visualization. Challenges I encountered during the execution of my experiment dealt with finding the cirrect number of trials and generations per trial that would accurately represent the experiment.

The results that I obtained from this experiment included average numbers of standard young tableau found per trial, as well as the total numbers of standard young tableau found. The total number of standards that were found was 413 after creating 5 million young tableau. As a note, there are 288 standard young tableau of shape (5,4,1). The average number of standard young tableau generated per trial was 8.3. about 8 per every 100,000 generated is really bad, as 99,992 computations are completly wasted. Below is a chart that helps to vizualise these results.

![Prototype Experiment Chart](/static/fa-icons/prototype_experiment.png)