## Problem Statement: 

At what point will total electrical generation in the United States first be made up of 50% renewable resources?

### Important Links: 

- https://www.eia.gov/electricity/data/browser/ Monthly data from January 2001 to April 2019

- https://www.eia.gov/totalenergy/data/annual/showtext.php?t=ptb0802a Yearly data from 1949 to 2011

- https://github.com/facebook/prophet Source code for Facebook Prophet

## cleaning/munging

Cleaned and separated data into a format I could use it.

## EDA

Learned to better understand my data, implemented further feature engineering. 

## modeling

I tried a few methods, but the one standardized through each notebook is Facebook Prophet, from which predictions were generated and conclusions were able to be reached.

*Note:* For each notebook, run the imports once with Prophet, then comment that line out. Otherwise, plotting throws an exception.

## conclusions

After going through my predictions and coming to a conclusion in the Cumulative Modeling notebook, the Conclusions notebook is where everything comes together and final predictions are delivered.

## Data Dictionary:

| Name                    | Use                                                                                    |
|-------------------------|----------------------------------------------------------------------------------------|
| Coal                    | Total of Coal                                                                          |
| Petroleum               | Total of Petroleum(including Petroleum Coke and Petroleum Liquids)                     |
| Natural Gas             | Total of Natural Gas                                                                   |
| Other Gases             | Total of other, miscellaneous gases                                                    |
| Nuclear                 | Total of Nuclear energy                                                                |
| Wind                    | Total of Wind energy                                                                   |
| Solar                   | Total of Solar energy(Includes small scale home photovoltatic and utility-scale Solar) |
| Hydroelectric           | Total of Hydroelectric Energy                                                          |
| Biomass                 | Total of Biomass energy(includes Biomass wood and Biomass Waste)                       |
| Geothermal              | Total of Geothermal energy                                                             |
| Renewable Total         | Total of all Renewables                                                                |
| Nonrenewable Total      | Total of all Nonrenewables                                                             |
| Total                   | Total energy generated                                                                 |
| Renewable Percentage    | Percentage of all energy derived from renewable sources                                |
| Nonrenewable Percentage | Percentage of all energy derived from nonrenewable sources                             |

