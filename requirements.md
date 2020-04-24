# Requirements

## Project Description
### Problem
Want to see analyzed data about the property market. 
</br>
Particularly:
- the price for 1 m<sup>2</sup> property
- the change of the price (during the time)
- the average property size per farmer

### Existing Solutions
TBD

### Our Goal
Create analytics tool for the property market which will show price for 
the 1 m<sup>2</sup> property, its change during the time for selected filters

### Input Requirements
- collect data from different sources
- the sources can be changed during the time (their numbers and their data also)
- the collected raw data should be saved as it is and there should be no way to clear/edit this data
- the collected raw data should be saved separate (physically) from processed data
- the data from sources can have different format
- the data from the same source can have different format during the time
- the data should be saved either it processed successfully or no
- there is no guarantee on the correctness of the data (as correctness we mean the content details)
- it should allow us to correct not valid incoming data
- the corrected data act as a separate source
- the same data can come from different sources
- the same data cam come from the same source many times (with the different format)
- we need to merge them during the processing

### Output Requirements
#### Average Analytics
- show average price for 1 m<sup>2</sup> property (filtered with specified filters)
- show distribution of areas by sizes (in other words, the average size of property)
- allow users to filter with following parameters:
   * time/duration
   * area (predefined in the system)
 
#### Collected Data
- show collected data with above filters

## Architecture
## User Path
## Design mockups or wireframes
## Tech Stack Related Info


