# Final Project OCN 682
### Author: Retno Kusuma Ningrum

Welcome to the repository for my Final Project in OCN 682. This project utilizes data from my previous work with WWF Indonesia, specifically from the Leatherback Turtle Conservation Project on Buru Island, Indonesia.

## Purpose  
The primary goal of this project is to create a comprehensive webpage that narrates the story of the Leatherback Turtle Conservation Project. It will cover everything from the preliminary study to the current impacts and updates.

## Benefit  
The final webpage will serve as a resource that can be shared with government agencies, donors, and other stakeholders interested in the Leatherback Turtle Conservation Project on Buru Island.
Using R as the platform to build this page streamlines the process of updating the story, as new data can be easily incorporated and reprocessed to refresh the content.

## Data Dictionary

### `monitoring.csv`

|variable                    |class     |description                           |
|:---------------------------|:---------|:-------------------------------------|
|MM                          |numerical |Month in number 1 to 12. 1 (January), 2(February, 3(March), 4(April), 5(May), 6(June), 7(July), 8(August), 9(September), 10(October), 11(November), 12(December). |
|YYYY                        |numerical |Year when the data were recorded between 2017 to 2023. |
|Date                        |integer   |Exact date when the data were recorded|
|HRS                         |numerical |Hours when the data were collected. |
|MIN                         |numerical |Minutes when the data were collected. |
|Nest_Type                   |character |Type of crawls were recorded: Nest (successful nesting attempt, but did not meet the turtles), Nesting_Individu (successful nesting attempt, and meet the turtles), False_Crawks (unsuccessful nesting attempt). |
|Nest_Disturbance            |character |Is the turtle nest disturbed? Secure (turtle nest is safe, undisturbed), Non_Nesting (associated with false crawls, non nesting activity), Lost (nest were lost due to illegal harvest), Predated (nest were predated by animals). |
|X                           |numerical |Latitude of the nest position coordinate |
|Y                           |numerical |Longitude of the nest position coordinate |

### `turtle_sighting.csv`

|variable                    |class     |description                           |
|:---------------------------|:---------|:-------------------------------------|
|species                     |character |Species of turtles using the common name. |
|total                       |numerical |Total report of turtle sighting. |  

### `when_sighting.csv`

|variable                    |class     |description                           |
|:---------------------------|:---------|:-------------------------------------|
|when                        |character |type of activities when informant see turtles. |
|total                       |numerical |Total report of turtle sighting in certain activity. |
