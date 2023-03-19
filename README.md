# DSAI
A mini project for SC1015 (Introduction to Data Science and Artificial Intelligence)

## Team Members
Ang Jo Wee (contributions)
Park Jihae (contributions)
Leong Mininn Miko (contributions)

## Problem Statement
Mushroom hunting, or "shrooming", has become increasingly popular as a recreational activity. However, correctly identifying edible mushrooms from poisonous ones can be challenging, even for experienced mushroom hunters. This poses a risk to the safety of mushroom hunters and their companions, as well as the general public if contaminated mushrooms are consumed.

## Problem Motivation

The goal of this project is to develop an accurate and reliable machine learning model for mushroom classification that classifies edibile and poisonous mushrooms, enhancing the safety of mushroom hunting activities.

## Attribute Information:
- classes: edible=e, poisonous=p
- cap-shape: bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s
- cap-surface: fibrous=f,grooves=g,scaly=y,smooth=s
- cap-color: brown=n,buff=b,cinnamon=c,gray=g,green=r,pink=p,purple=u,red=e,white=w,yellow=y
- bruises: bruises=t,no=f
- odor: almond=a,anise=l,creosote=c,fishy=y,foul=f,musty=m,none=n,pungent=p,spicy=s
- gill-attachment: attached=a,descending=d,free=f,notched=n
- gill-spacing: close=c,crowded=w,distant=d
- gill-size: broad=b,narrow=n
- gill-color: black=k,brown=n,buff=b,chocolate=h,gray=g,green=r,orange=o,pink=p,purple=u,red=e,white=w,yellow=y
- stalk-shape: enlarging=e,tapering=t
- stalk-root: bulbous=b,club=c,cup=u,equal=e,rhizomorphs=z,rooted=r,missing=?
- stalk-surface-above-ring: fibrous=f,scaly=y,silky=k,smooth=s
- stalk-surface-below-ring: fibrous=f,scaly=y,silky=k,smooth=s
- stalk-color-above-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
- stalk-color-below-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
- veil-type: partial=p,universal=u
- veil-color: brown=n,orange=o,white=w,yellow=y
- ring-number: none=n,one=o,two=t
- ring-type: cobwebby=c,evanescent=e,flaring=f,large=l,none=n,pendant=p,sheathing=s,zone=z
- spore-print-color: black=k,brown=n,buff=b,chocolate=h,green=r,orange=o,purple=u,white=w,yellow=y
- population: abundant=a,clustered=c,numerous=n,scattered=s,several=v,solitary=y
- habitat: grasses=g,leaves=l,meadows=m,paths=p,urban=u,waste=w,woods=d

## Files
- data.csv
- index.ipynb (notebook)
- index.html (html ver where you can view as a website)
- presentation.pptx (presentation deck)

## EDA
- what you want to find out
- what code did you use to derive your result
- analyse the graph/diagram/table etc on what does it show

## Data Preparation
- Did not do much except for one hot encode data as there are no null or duplicated values

## Models used
We would like to find out using which learning algorithm will create the most accurate model. We are comparing 3 models:
- Logistic Regression
- Random Forest
- Support Vector Machines (SVM)

## Conclusion/Insights gained
