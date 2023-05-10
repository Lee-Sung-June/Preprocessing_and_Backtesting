# Preprocessing_and_Backtesting

This code is about preprocessing and backtesting korean stocks using pandas.

It includes factors as "PBR", "GP/A", "PER", "ROE", "Investment psychological line(Monthly)", 
and cutting firms which have market cap under 100 billion won.

The number of groups in the test is 5, each are sorted according to the factors above.
Weights of the factors used in making portfolio groups are arbitrary.

The whole backtesting is from June, 2006 to June, 2022 and has one-year rebalancing period.

The result of cumulative excess returns of the five group portfolio seems not satisfied for early few years,
but has significant difference in the long term.
