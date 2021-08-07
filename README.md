# Module 09 Challenge - Surfing Climate Analysis

## Overview

The purpose of this analysis is to present additional information related
to temperature data for the months of June and December in Oahu, Hawaii.

### Deliverables:
1. Summary Statistics for June
2. Summary Statistics for December
3. This written report

### Resources

- Software:
	- Jupyter notebook server 6.3.0, running Python 3.7.10 64-bit (Dependencies: datetime, matplotlib, numpy, pandas, sqlalchemy)
- Data: Weather Station Data Acquired from NOAA Weather Stations in the US State of Hawaii. Stored in a SQLite Database and provided by potential investor W. Avy:
	`hawaii.sqlite`

Additional information about these resources is outlined below in Table 1.

**Table 1:**
| File Name                   | Brief Description of Contents |
|-----------------------------|-------------------------------|
|`hawaii.sqlite`              |SQLite Database containing two Tables: `measurement` and `station`.<br />The `measurement` Table contains Five (5) fields, `id`, `station`, `date`, `prcp`, and `tobs`.<br />The `stations` Table contains Six (6) fields, `id`, `station`, `name`, `latitude`, `longitude`, and `elevation`.<br /><br />Contains 19,550 Measurement Observations taken from Nine (9) NOAA Weather Stations in the US State of Hawaii between the dates of January 01, 2010 and August 23, 2017.|

Further detail about the data-containing fields of the Tables in `hawaii.sqlite` is outlined below in Table 2.

**Table 2:**
| Table Name                  | Field Name     | Brief Description of Field and Contents |
|-----------------------------|----------------|-----------------------------------------|
|`measurement`                |`id`            |Unique id number of measurement observation, maximum one per station per day [Not all Stations reporting measurements for all days]. One observation consists of *one* `prcp` Precipitation Measurement and *one* `tobs` Temperature Measurement, associated with the specified `station` on the given `date`. Time of observation on `date` is uncertain.
|                             |`station`       |Unique station id, consisting of 3-letter Capital Alpha Code Followed by 8-digit Numeric Identifier.
|                             |`date`          |Gregorian Calendar date, ISO 8601 Formatted as 'YYYY-MM-DD'
|                             |`prcp`          |Total Observed Precipitation on `date`, US Customary Inches (Reported as Decimal Inches to the Hundredth Place in the form of dd.dd).
|                             |`tobs`          |Observed Temperature on `date`, Degrees Fahrenheit (Reported as Whole Degrees in the form of dd.0).
|`stations`                   |`id`            |Unique id number of station listing.
|                             |`station`       |Unique station id, consisting of 3-letter Capital Alpha Code Followed by 8-digit Numeric Identifier.
|                             |`name`          |Descriptive Name of Station, Capitalized free text.
|                             |`latitude`      |NAD83 Latitude of `station` location, in decimal form dd.xxxx (Positive North, Negative South).
|                             |`longitude`     |NAD83 Longitude of `station` location, in decimal form dd.xxxx (Positive East, Negative West).
|                             |`elevation`     |NAD83 Elevation of `station` location, SI-Meters (Reported as Decimal Meters to the Tenth Place in the form of ddd.d)

## Deliverables

### Deliverable 1

See `SurfsUp_Challenge.ipynb`, ***Deliverable 1***.


### Deliverable 2

See `SurfsUp_Challenge.ipynb`, ***Deliverable 2***.


### Deliverable 3

Describe the key differences in weather between June and December, and provide two recommendations for further analysis.

See ***Results*** and ***Summary*** Below.

## Results

Like many locations on Earth, Hawaii experiences seasonal fluctuation in weather patterns, that are measurable in terms such as Observed Temperature and Precipitation. This is in accordance with the rotation of the Earth, the procession of the Earth around the Sun, the change in relative axial position of the Earth's Axis to the Sun, the relative distance of the Earth to the Sun in accordance with its elliptical orbit, and other environmental factors. Depending on where a particular location is situated on Earth, the given seasonal fluctuation can be extreme or mild, according to environmental factors such as distance from the equator, distance to the nearest ocean or large body of water, trade winds, prevailing ocean currents, atmospheric conditions, solar activity, near or distant volcanic activity, or climate change--anthropogenic or otherwise.

For the time being in this analysis, we will confine ourselves to the discussion of Temperature by itself, and leave any discussion regarding Precipitation for another day.

Concerning Hawaii specifically, there is an observable regular pattern of seasonal temperature variation. Without delving deeply into the scientific reasons why, owing to the conditions alluded to above, the seasonal variations in observed temperature measured in Hawaii throughout the course of a typical year could be described as *mild* according to the judgement of an average Human Person.

During the time period under study, the highest temperature observed was 87.0 deg F, and the lowest was 53.0 deg F.

- Difference 1
- Difference 2
- Difference 3

## Summary

Two additional queries that could be performed to gather more weather data for June and December:
1. yyyy
2. zzzz
