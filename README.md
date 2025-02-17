# Project-01: Exploratory Data Analysis (EDA) Projects of MTA Turnstile Data:

This repo contains Project-01 data and solution at Istanbul Data Science Academy. Project-01 is about Exploratory Data Analysis (EDA) of Metropolitan Transportation Authority (MTA) Turnstile Data.

## Exploratory Data Analysis (EDA):
Exploratory Data Analysis (EDA) is an approach to analysing data set to summarise their main characteristic, often with visual methods. (Wikipedia)

## Objective and Goal:
We are a company that places vending machines in different parts of the city. We have 5 vending machines to put on the New York subway. In order to get a better income from vending machines, we analyze places with high human density. We will install these vending machines in the 5 busiest metro stations.

## About MTA:
The Metropolitan Transportation Authority is North America's largest transportation network, serving a population of 15.3 million people across a 5,000-square-mile travel area surrounding New York City through Long Island, southeastern New York State, and Connecticut.
The MTA network comprises the nation’s largest bus fleet and more subway and commuter rail cars than all other U.S. transit systems combined. The MTA's operating agencies are MTA New York City Transit, MTA Bus, Long Island Rail Road, Metro-North Railroad, and MTA Bridges and Tunnels.

## MTA Turnstile Data:
Data obtained from [http://web.mta.info/developers/turnstile.html](http://web.mta.info/developers/turnstile.html).

## Field Description:

| Field Name | Description |
|------------|-------------|
| C/A | Control Area (A002) |
| UNIT |	Remote Unit for a station (R051)|
| SCP | Subunit Channel Position represents an specific address for a device (02-00-00)|
| STATION | Represents the station name the device is located at |
| LINENAME | Represents all train lines that can be boarded at this station |
| DIVISION | Represents the Line originally the station belonged to BMT, IRT, or IND |
| DATE | Represents the date (MM-DD-YY)|
| TIME | Represents the time (hh:mm:ss) for a scheduled audit event |
| DESC | Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours) |
| ENTRIES | The comulative entry register value for a device |
| EXITS | The cumulative exit register value for a device |

### Example:
The data below shows the entry/exit register values for one turnstile at control area (A002) from 09/27/14 at 00:00 hours to 09/29/14 at 00:00 hours

```txt
C/A,UNIT,SCP,STATION,LINENAME,DIVISION,DATE,TIME,DESC,ENTRIES,EXITS.

A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-27-14,00:00:00,REGULAR,0004800073,0001629137
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-27-14,04:00:00,REGULAR,0004800125,0001629149
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-27-14,08:00:00,REGULAR,0004800146,0001629162
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-27-14,12:00:00,REGULAR,0004800264,0001629264
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-27-14,16:00:00,REGULAR,0004800523,0001629328
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-27-14,20:00:00,REGULAR,0004800924,0001629371
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-28-14,00:00:00,REGULAR,0004801104,0001629395
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-28-14,04:00:00,REGULAR,0004801149,0001629402
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-28-14,08:00:00,REGULAR,0004801168,0001629414
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-28-14,12:00:00,REGULAR,0004801304,0001629463
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-28-14,16:00:00,REGULAR,0004801463,0001629521
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-28-14,20:00:00,REGULAR,0004801737,0001629555
A002,R051,02-00-00,LEXINGTON AVE,456NQR,BMT,09-29-14,00:00:00,REGULAR,0004801836,0001629574
```