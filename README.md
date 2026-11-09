# Does El Niño Strength Matter for Commodity Prices?

**Full analysis (Kaggle notebook): https://www.kaggle.com/code/milesluis/does-el-ni-o-strength-matter-for-commodity-prices**

An event study of how corn, wheat, soybeans, coffee and sugar prices responded to 22 El Niño events since 1960, comparing regular events with the three "super" El Niños (1982-83, 1997-98, 2015-16).

## Key finding
For four of the five commodities, super El Niño events don't just amplify the price response. They reverse its direction. Coffee, for example, averaged +7.8% at 12 months after regular events and -33.3% after super events. Corn was the only commodity that stayed on the same side of zero.

## Methods
- Event identification: NOAA Oceanic Niño Index (ONI), with a +2.0°C threshold for "super"
- Price data: World Bank Pink Sheet (1960 onward) and Yahoo Finance futures (2000 onward)
- Analysis: percent price change at 3, 6 and 12 months after onset, plus a supplementary linear regression
- Forecast: the 2026-27 event, with predictions dated and set to be revisited in March 2027

## Limitations
Only three super El Niño events exist, so averages are sensitive to any single event. This analysis shows correlation, not proven causation.
