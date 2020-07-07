# VBA of Wall Street

## Overview of Project

### Purpose
Performing analysis on price data for green stocks to provide yearly returns and total volumes. This information will provide a rough guideline as to how well these stocks are performing and whether or not to invest in them.

## Results

Below are the returns and total volumes for the selected stocks:

![Results_2017](/Resources/Results_2017.png) ![Results_2018](/Resources/Results_2018.png)

Using the initial code, the analysis took approximately 0.5 seconds for 2017 and 0.48 seconds for 2018 data.

![VBA_Challenge_2017_Initial_Script](/Resources/VBA_Challenge_2017_Initial_Script.png) ![VBA_Challenge_2018_Initial_Script](/Resources/VBA_Challenge_2018_Initial_Script.png)

Using the refactored code, the analysis took approximately 0.09 seconds for 2017 and 0.09 seconds for 2018 data.

![VBA_Challenge_2017](/Resources/VBA_Challenge_2017.png) ![VBA_Challenge_2018](/Resources/VBA_Challenge_2018.png)

## Summary

An advantage of refactoring is that it potentially optimizes code to run faster by using less memory and/or taking less steps, which is important when working with large data sets. A disadvantage is that this can be a time consuming process, and that time could be used on writing code to solve other problems.

With this script specifically, the refactored script is much faster and takes about 0.1 seconds to run while the initial script took around 0.5 seconds, putting it at a speed advantage. However, the code in the refactored script is less flexible as it relies on the tickers to be in the same order; if data came in for the next year and one of the tickers was not on it, the script would be at a disadvantage as it would no longer provide all of the results.