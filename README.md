# Module 11 Challenge - UFOs - JavaScript
## Overview
The purpose of this assignment is to update and republish a website that shows UFO information.

The website hosts an interactive table that contains summary information about UFO Sightings.

The first version for the website allowed the user to input a date and receive the information from the table. However, the second version allows the user to input additional filters for Date, City, State, Country, and Shape. The act of inputting the values should be enough to update the tables.

Deliverables
1. Updated Version 2.0 of webpage which filters UFO Sightings on multiple criteria.
2. This written report (README.md)

There are the data fields that need to the incorporated into the website.

**Table 1: data.js Fields**
| Field Name               | Brief Description of Field and Contents|
|--------------------------|----------------------------------------|
| `datetime`               | Formatted as 'mm/dd/yyyy'
| `city`                   | City [lowercase]
| `state`                  | State [lowercase]
| `country`                | Country [lowercase]
| `shape`                  | Shape [lowercase]
| `durationMinutes`        | Description of duration of observation, in minutes. Field is free text, and standards on original input have been loosely enforced. [lowercase, limited format orthodoxy]
| `comments`               | Free Text comment providing additional information on observation. [Mixedcase, limited format orthodoxy]

## Results
The new version of the website allows the user to easily input filter the data table through one of 5 fields: Date, City, State, Country, and Shape.
The input boxes make the website flexible and intuitive. If no user-specified filters are entered, the entire table of data is shown. additionally, any combination of filters boxes work and HTML is refreshed after input. 

The website was then uploaded using GitHub pages to: 
https://iffadanwar.github.io/

**Figure 1: Webpage**

<img src=https://raw.githubusercontent.com/Iffadanwar/UFOs/main/static/images/DILIV%201.png>

## Summary

The website is quickly and easily able to parse through the information present on the website using a variety of filters and techniques. The website was then hosted using Github pages and made public as shown above.

One major problem with the website is that there is no export functionality. If a user wants to save a result, they would have to record it themselves or copy the HTML tab directly. An excellent feature would be to allow a user to save their results locally to their computer via a CSV file.

### Recommendations for Further Development
1. Incorporate a File Export Functionality for End Users.
2. Incorporate a clear filter button to make resetting the data table faster and more efficient.
