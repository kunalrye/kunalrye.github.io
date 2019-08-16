---
title: ":hammer: Tool Development @ Lockheed Martin"
layout: post
date: 2018-05-08 22:10
# tag: jekyll
# image: 
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "My first SWE internship"
category: project
author: kunalrai
externalLink: false
---
<!-- ![image](assets/images/LM-logo.png) -->
<img src="assets/images/LM-logo.png" width="800" />

## Creating a standalone tool
My first project at LM Aeronautics was to develop a standalone tool that created a monetary value for software updates that were made to the F-35. I had to take a dataset of past software changes that had a calculated monetary value and determine how to predict the value that a new software update would provide. Since this software was related to the performance of a physical fighter jet, there were quite a few variables to consider. 

### Process
In order to come up with predictions, I had to understand how the current predictions were being calculated. I took a period to understand the factors, meet with SME's who provided data, and pre-process the data before developing the tool. 

### Development
Due to software constraints, I had to open myself to new development options. Given that the tool needed to be portable and the output easily understandable for presentation, I decided to pickup Visual Basic for Applications and develop the tool in an excel spreadsheet. It was very different coming from Python but I was able to learn quite a bit about the limitations and benefits of my choice. Ultimately, the tool had a simple GUI, worked quickly and intuitively, while producing predictions of value within 15% of the actual value. 
