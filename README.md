# ACM Research coding challenge (Fall 2022)

## My Problem and Solution

Given the dataset of information about cars, I set out to provide a bunch of different methods that could prove useful to people interested to buying cars. These methods would be able to do things people commonly do when looking for cars.

## Best Car for a certain characteristic

In this method, I gave the user options for multiple different car characteristics given in the data set. I let them choose which characteristics they want to explore and then displayed them a car that is typically more favorable for that characteristic. For example, the lowest price, lowest mileage, or highest ratings.

## Best Car for All Characteristics

This method does the same thing as the previous one except it doesnt give the user the choice and instead displays the car most favorable for each characteristic that I could rank.

## Nearest cars to a certain budget

In this method, the user inputs their budget and a certain amount of money they are willing to deviate from that budget, lower or higher. I then found every car within that range and showed it to the user along with its price.

## All Cars under a certain budget

Similar to the last method, except in this one it just displays all the cars and their prices below the inputed budget.

## More information about a certain car

This method takes in the year, make, and model of a car and outputs all the information for that car or cars depending on if multiple vehicles satisfy the conditions. I couldn't get the method to work, but my code is there. If I had gotten the method to work, I would have added failsafes in case the car entered doesnt exist.
