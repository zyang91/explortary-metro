# Report

**Author: Zhanchao Yang, Chuwen Zhong**

# Introduction & Research Questions

Bogotá, long served by an extensive bus network yet plagued by chronic congestion and air pollution, is on the cusp of a major transit transformation. The city’s first metro lines—Line 1, which will link the northwest suburbs with the city center, and Line 2, running through the northern corridor—promise not only faster, more reliable journeys but also substantial environmental and socio-economic benefits. However, the success of this infrastructure depends as much on engineering and finance as on public buy-in: how citizens perceive its effectiveness, its impact on air quality and noise, and its broader effects on livelihoods and equity.

This study examines how near subway line household perception different between Line 1 and Line 2, and how socio-economic factors influences their perception

By illuminating the perceptions held by various communities, we aim to inform both policy adjustments and communication strategies that will maximize public support and ensure that Bogotá’s metro delivers on its promise of cleaner, more equitable urban mobility.

# Method
## Sampling and Participants
This study employs a cross-sectional survey design to compare household perceptions and socio-economic profiles along Bogotá Metro Line 1 (elevated) and Line 2 (underground). A total of 537 households were collected, with 290 completed responses for Line 1 and 247 for Line 2 (response rates of 72.5% and 61.8%, respectively).


## Data Processing and Analysis
- **Data Cleaning**: Responses were exported to R, where invalid entries were removed and categorical variables were recoded (e.g., income brackets standardized).
- **Descriptive Statistics**: Frequencies and percentages were calculated for all variables by corridor.
- **Comparative Analysis**: Chi-square tests assessed significant differences in categorical responses between Line 1 and Line 2 households. （*potential next steps*)
- **Visualization**: Bar charts and cross-tabulations were generated to illustrate key contrasts.

All analyses were performed in R version 4.2.2, using packages ·dplyr·, ·ggplot2·.

# Results

The Results section presents a comparative overview of demographic profiles, travel behaviors, perception metrics, and implementation expectations among households adjacent to Metro Line 1 and Line 2. We begin by summarizing general socio‑demographic characteristics before exploring shifts in travel modes pre‑ and during the pandemic. Next, we examine attitudes toward the upcoming metro service—covering efficiency, safety, and environmental perceptions—followed by anticipated community impacts post‑implementation.

## General demographics

### P1. What type of housing do you live in?
| Housing Type         | Metro 1         | Metro 2         |
| ------------------------- | --------------- | --------------- |
| Casa      | 173 (59.9%)     | 163 (66%)     |
| Apartamento        | 97 (33.6%)     | 76 (30.8%)     |
| SCuarto(s) en inquilinato | 13 (4.5%)     | 6 (2.4%)     |
| Cuarto(s) en otro tipo de vivienda| 6 (2.1%)     | 0     |
| Otro tipo de vivienda| 0      | 2 (0.8%)      |


### P3. What is the total number of people in your household?

| # of people         | Metro 1         | Metro 2         |
| -- | --------------| -------------- |
| 1 | 71 (24.6%)     | 39 (15.8%)     |
| 2 | 76 (26.3%)     | 68 (27.3%)     |
| 3 | 68 (23.5%)     | 63 (25.5%)     |
| 4 | 34 (11.8%)     | 55 (22.3%)     |
| 5 | 27 (9.3%)      | 15 (6.1%)      |
| Over 5| 13 (4.5%)      | 7 (2.8%)      |


### P42. In 2019, before the COVID-19 pandemic, what was the primary means of transportation you used for your daily commute?

| Mode             | Line 1       | Line 2        | Total |
|------------------|--------------|---------------|-------|
| BRT              | 117 (40.5%)  | 90 (36.4%)    | 207   |
| Bicycle          | 21 (7.3%)   | 34 (13.8%)    | 55    |
| Car              | 22 (7.6%)   | 22 (8.9%)    | 44    |
| Intermunicipal   | 15 (5.2%)   | 8 (3.2%)     | 23    |
| Motorcycle       | 22 (7.6%)   | 14 (5.7%)    | 36    |
| Other            | 11 (3.8%)   | 13 (5.3%)    | 24    |
| Other Private    | 0 (0.0%)     | 1 (0.4%)    | 1     |
| Other Public     | 3 (1.0%)    | 2 (0.8%)     | 5     |
| SITP             | 36 (12.5%)   | 40 (16.2%)    | 76    |
| Taxi             | 16 (5.5%)   | 5 (2%)     | 21    |
| Walk             | 26 (9%)   | 18 (7.3%)    | 44    |



### P43. In 2020, during the COVID-19 pandemic, what was the primary means of transportation you used for your daily commute?

| Mode             | Line 1       | Line 2        | Total |
|------------------|--------------|---------------|-------|
| BRT              | 70 (24.2%)  | 55 (15.8%)    | 125   |
| Bicycle          | 27 (9.3%)   | 39 (15.8%)    | 66    |
| Car              | 24 (8.3%)   | 23 (9.3%)    | 47    |
| Intermunicipal   | 9 (3.1%)   | 3 (1.2%)     | 12    |
| Motorcycle       | 14 (4.8%)   | 10 (4%)    | 24    |
| Other            | 41 (14.2%)   | 41 (16.6%)    | 82    |
| Other Private    | 2 (0.7%)     | 2 (0.8%)    | 4     |
| Other Public     | 2 (0.7%)    | 5 (2%)     | 7     |
| SITP             | 23 (8.0%)   | 32 (13.0%)  | 55    |
| Taxi             | 20 (6.9%)   | 11 (4.5%)     | 31    |
| Walk             | 57 (19.7%)   | 26 (10.5%)    | 83    |


### P50. Monthly income

| Income   | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
|$0 – $400,000| 5 (2.5%)    | 8 (3.6%)    |
|$400,001 – $800,000| 23 (11.5%)    | 15 (6.7%)    |
|$800,001 – $1,160,000| 26 (13%)    | 27 (12.1%)    |
|$1,160,000 – $1,500,000| 31 (15.5%)  | 54 (24.2%)  |
|$1,500,001 – $2,000,000| 24 (12%)    | 42 (18.8%)  |
|$2,000,001 – $2,500,000| 25 (12.5%)  | 27 (12.1%)  |
|$2,500,001 – $3,500,000| 33 (16.5%)  | 20 (9%)     |
|$3,500,001 – $4,900,000| 18 (9%)     | 21 (9.4%)   |
|$4,900,001 – $6,800,000| 10 (5%)     | 7 (3.1%)    |
|$6,800,001 – $9,000,000| 4 (2%)      | 1 (0.4%)    |
|Más de $9,000,000| 1 (0.5%)    | 1 (0.4%)    |

## Information availability & General perception

### P58. Metro Quick and Efficient (public transportation not metro project
| Response | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
| Yes      | 181 (62.62%)    | 132 (53.44%)    |
| No       | 108 (37%)       | 115 (46.55%)    |


### P59. Benefit your physical and psychological health
| Response | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
| Yes      | 129 (44.63%)    | 94 (38.05%)     |
| No       | 160 (55.36%)    | 153 (61.94%)    |


### P60. Routes have enough information
| Response | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
| Yes      | 169 (58.47%)    | 136 (55.06%)    |
| No       | 120 (41.52%)    | 111 (44.93%)    |


### P61. On-time and reliable
| Response | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
| Yes      | 118 (40.83%)    | 101 (40.89%)    |
| No       | 120 (59.17%)    | 146 (59.11%)    |


### P62. Environmentally friendly
| Response | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
| Yes      | 165 (57.09%)    | 133 (53.85%)    |
| No       | 124 (42.91%)    | 114 (46.15%)    |


### P63. Safe transportation option
| Response | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
| Yes      | 108 (37.37%)    | 88 (35.63%)     |
| No       | 181 (62.63%)    | 159 (64.37%)    |


### P64. Prefer other transportation option
| Response | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
| Yes      | 191 (66.09%)    | 174 (70.44%)    |
| No       | 98 (33.91%)     | 73 (29.56%)     |


### P65_1. Most important factors in travel
| Factor                     | Metro 1         | Metro 2         |
| -------------------------- | --------------- | --------------- |
| Time of trips              | 78 (26.99%)     | 54 (21.86%)     |
| Closeness of station       | 26 (8.99%)      | 27 (10.93%)     |
| Comfort during trip        | 40 (13.84%)     | 19 (7.69%)      |
| Security on the system     | 80 (27.68%)     | 81 (32.79%)     |
| Cost of travel             | 31 (10.72%)     | 13 (5.26%)      |
| Environmental impacts      | 5 (1.73%)       | 2 (0.81%)       |
| Punctuality of buses       | 29 (10.03%)     | 51 (20.64%)     |

### P66. Do you perceive that, in general, your usual journeys, due to the construction of the LMB (Bogotá Metro Line), take more, less or the same amount of time?
| Time change                | Metro 1         | Metro 2         |
| -------------------------- | --------------- | --------------- |
| take more time             | 191 (66.1%)     | 143 (57.9%)     |
| same amount of time        | 70 (24.2%)      | 53 (21.5%)      |
| less amount of time        | 28 (9.7%)       | 51 (20.6%)      |


### P67. On a scale of 1 to 6 where 1 means “Very pessimistic” and 6 “Very optimistic”, about the project and its implementation, do you feel:
| Scale                     | Metro 1         | Metro 2         |
| ------------------------- | --------------- | --------------- |
| 1 (Very pessimistic)      | 17 (5.9%)       | 34 (13.8%)      |
| 2                         | 16 (5.5%)       | 12 (4.9%)       |
| 3                         | 53 (18.3%)      | 54 (21.9%)      |
| 4                         | 51 (17.6%)      | 48 (19.4%)      |
| 5                         | 51 (17.6%)      | 41 (16.6%)      |
| 6 Very Optimistic         | 101 (34.9%)     | 58 (23.5%)      |


### P68. Support or not support
| Response | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
| Yes      | 271 (93.77%)    | 220 (89.07%)    |
| No       | 18 (6.23%)      | 27 (10.93%)     |


### P69_1. First statement major disagreement
1. The metro is elevated
2. Distrust in the district's ability to manage and properly maintain the metro system
3. Environmental impact
4. Noise impact
5. Fears about potential expropriation of properties or displacement of local communities
6. Preference for other forms of transportation
7. Financial costs of developing the project
8. Concerns about traffic congestion during metro construction

![image](https://github.com/user-attachments/assets/9c2fb2e3-23dc-45e3-96fd-9002330e301b)


### P70. Information availability: Infrastructure type (underground, surface, and elevated)
| Information level         | Metro 1         | Metro 2         |
| ------------------------- | --------------- | --------------- |
| No information at all     | 98 (33.91%)     | 93 (37.65%)     |
| Little information        | 79 (27.33%)     | 68 (27.53%)     |
| Some information          | 64 (22.14%)     | 49 (19.84%)     |
| A lot of information      | 38 (13.15%)     | 27 (10.93%)     |
| All information           | 10 (3.46%)      | 10 (4.05%)      |


### P71. Information availability: Metro Route
| Information level         | Metro 1         | Metro 2         |
| ------------------------- | --------------- | --------------- |
| No information at all     | 120 (41.52%)    | 112 (45.44%)    |
| Little information        | 73 (25.26%)     | 68 (27.53%)     |
| Some information          | 55 (19.03%)     | 46 (18.62%)     |
| A lot of information      | 32 (11.07%)     | 15 (6.07%)      |
| All information           | 9 (3.11%)       | 6 (2.43%)       |

### P72. Information availability: Location of future stations of the Bogota Metro Line
| Information level         | Metro 1         | Metro 2         |
| ------------------------- | --------------- | --------------- |
| No information at all     | 132 (45.67%)    | 132 (53.44%)    |
| Little information        | 85 (29.41%)     | 70 (28.34%)     |
| Some information          | 49 (16.95%)     | 26 (10.52%)     |
| A lot of information      | 18 (6.23%)      | 12 (4.86%)      |
| All information           | 5 (1.73%)       | 7 (2.83%)       |


### P73. Estimated year of operation
| Information level         | Metro 1         | Metro 2         |
| ------------------------- | --------------- | --------------- |
| No information at all     | 155 (53.63%)    | 138 (55.87%)    |
| Little information        | 61 (21.11%)     | 63 (25.50%)     |
| Some information          | 44 (15.22%)     | 26 (10.52%)     |
| A lot of information      | 22 (7.61%)      | 16 (6.48%)      |
| All information           | 7 (2.42%)       | 4 (1.62%)       |

### P78. Will you use it, based on current information?
| Response | Metro 1         | Metro 2         |
| -------- | --------------- | --------------- |
| Yes      | 268 (92.73%)    | 255 (91.09%)    |
| No       | 21 (7.27%)      | 22 (8.91%)      |


### P81. If it were to go into operation tomorrow, what is the maximum amount you would be willing to pay for a ticket on the Bogotá Metro?
| Pay level            | Metro 1         | Metro 2         |
| -------------------- | --------------- | --------------- |
| lower or equal to $3200     | 209 (72.3%)     | 186 (75.3%)     |
| $3200 - $3500        | 54 (18.7%)      | 41 (16.6%)      |
| $3500 - $3800        | 18 (6.2%)       | 14 (5.7%)       |
| $3800 - $4100        | 5 (1.7%)        | 3 (1.2%)        |
| $4100 - $4500        | 2 (0.7%)        | 0               |
| More than $4500      | 1 (0.3%)        | 3 (1.2%)        |

## Housing characteristics

### P82. Rent or own
| Status    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Rent      | 148 (51.21%)    | 173 (70.04%)    |
| Own       | 141 (48.79%)    | 74 (29.96%)     |


### P83. Length of residence
| Duration  | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| < 1 yr    | 37 (12.80%)     | 37 (14.98%)     |
| 1–5 yrs   | 83 (28.72%)     | 73 (29.55%)     |
| 5–10 yrs  | 52 (17.99%)     | 45 (18.21%)     |
| 10–15 yrs | 30 (10.38%)     | 19 (7.69%)      |
| 15–20 yrs | 21 (7.26%)      | 11 (4.45%)      |
| > 20 yrs  | 66 (22.83%)     | 62 (25.10%)     |


### P86. Monthly rent
| Range                      | Metro 1         | Metro 2         |
| -------------------------- | --------------- | --------------- |
| Less than $500,000         | 19 (15.2%)      | 9 (5.26%)       |
| $500,000 – $1,000,000      | 75 (60.0%)      | 83 (51.87%)     |
| $1,000,000 – $1,500,000    | 22 (17.6%)      | 47 (29.37%)     |
| $1,500,000 – $2,000,000    | 4 (3.2%)        | 12 (4.37%)      |
| $2,000,000 – $3,000,000    | 5 (4.0%)        | 2 (1.25%)       |

## After implement perception

### P87. Property value or rent
| Change    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Increase  | 152 (61.54%)    | 204 (70.59%)    |
| No change | 82 (33.20%)     | 80 (27.68%)     |
| Decrease  | 13 (5.26%)      | 5 (1.73%)       |


### P90. Community safety
| Change    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Increase  | 97 (33.56%)     | 66 (26.72%)     |
| No change | 126 (43.60%)    | 132 (53.44%)    |
| Decrease  | 66 (22.84%)     | 49 (19.84%)     |


### P91. Community living expense
| Change    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Increase  | 168 (58.13%)    | 153 (61.94%)    |
| No change | 114 (39.44%)    | 84 (34.82%)     |
| Decrease  | 7 (2.42%)       | 8 (3.24%)       |


### P92. Local commercial
| Change    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Increase  | 154 (53.29%)    | 136 (55.06%)    |
| No change | 112 (38.75%)    | 85 (34.41%)     |
| Decrease  | 23 (7.96%)      | 26 (10.53%)    |


### P95. Satisfaction of public transit
| Change    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Increase  | 142 (49.13%)    | 112 (45.34%)    |
| No change | 107 (37.02%)    | 86 (34.82%)     |
| Decrease  | 40 (13.84%)     | 49 (19.84%)     |

### P96. Commuting time
| Change    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Increase  | 59 (20.41%)     | 44 (17.81%)     |
| No change | 99 (34.26%)     | 84 (34.01%)     |
| Decrease  | 133 (45.33%)    | 119 (48.18%)    |

### P98. Noise pollution
| Change    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Increase  | 128 (44.29%)    | 121 (48.99%)    |
| No change | 107 (37.02%)    | 64 (25.91%)     |
| Decrease  | 54 (18.68%)     | 62 (25.10%)     |

### P100. Public space (sidewalk, green space, park)
| Change    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Increase  | 73 (25.26%)     | 75 (30.36%)     |
| No change | 137 (47.41%)    | 101 (40.89%)    |
| Decrease  | 79 (27.33%)     | 71 (28.74%)     |

### P101. New housing project
| Change    | Metro 1         | Metro 2         |
| --------- | --------------- | --------------- |
| Increase  | 153 (52.94%)    | 144 (58.30%)    |
| No change | 110 (38.06%)    | 72 (29.15%)     |
| Decrease  | 26 (9.00%)      | 31 (12.55%)     |

---

# Key Takeaway

### Demographics
- **Housing type**: Metro 2 has more single apartment homes than Metro 2.
- **Homeownership**: Metro 2 users are far more likely to own their homes (70.04%) than Metro 1 users (48.79%)
- **Household size**: Larger households (4+ members) are more common along Metro 2 (22.3% for four-person households) compared with Metro 1 (11.8%)

### Pre- and During-Pandemic Travel Modes
- **Bicycle use**: Before COVID-19, 13.8% of Metro 2 commuters biked versus 7.3% for Metro 1; during the pandemic, this rose to 15.8% (Metro 2) vs. 9.3% (Metro 1)
- **Walking**: Metro 1 saw higher walking rates during the pandemic (19.7%) compared to Metro 2 (10.5%)

### Socio-economic profiles
- **Income distributions**: Metro 1 has a higher share of respondents in the top income bracket of 2.5 – 3.5 million (16.5% vs. 9.0%), whereas Metro 2 peaks in the mid-range bracket of 1.16 – 1.5 million (24.2% vs. 15.5%)

### Perceptions and Attitudes
- **Quick and efficient**: A larger share of Metro 1 respondents felt the system would be quick and efficient (62.6%) versus Metro 2 (53.4%)
- **Optimism vs pessimism**: “Very optimistic” ratings were more common in Metro 1 (34.9%) than Metro 2 (23.5%), while Metro 2 had more “Very pessimistic” responses (13.8% vs. 5.9%)
- **Overall support**: Support for the project was higher in Metro 1 (93.8%) than in Metro 2 (89.1%)
- **Preference for other modes**: Metro 2 users were somewhat more inclined to choose other transport options (70.4%) compared to Metro 1 (66.1%)
- **Most important factors in travel**: Metro 2 pays more attention to **Punctuality of buses** (20% vs. 10%), while Metro 1 focuses more on **time of trips, comfort during trips, and cost of the trips**.
- **Optimism and support**: Metro 1 users are more optimistic about the metro system than Metro 2 households, and Metro 1 shows stronger support for the system's construction.

### Information and Awareness
In general, information availability is generally low for both metro one and metro two household. People are not sure the infrastructure type, metro route, station location, and estimated year of operations. People are more willing to pay lower price to ride the system.

- **Access to information**: Metro 1 respondents reported slightly better awareness of infrastructure details (13.2% “A lot of information” vs. 10.9%)

### After implemented perception
There is no statistically significant difference in implementation perception between Metro 1 and Metro 2 households.

## Summary
These patterns suggest that Metro 1 respondents tend to be more optimistic, better informed, and perceive greater benefits (efficiency, support) from the new line, while Metro 2 respondents—many of whom own their homes and live in larger households—exhibit higher cycling rates, greater concern for punctuality and security, and slightly less overall enthusiasm.
