# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
0.86. Menas the the general relationship between the regression and data does exist but its not strong.

2. Is your model accurate? Why or why not?
Not very accurate for the price. Guesses were ranging from 10-20% error from the real true values. Rare guesses were under 5% error and a few were above 100%

3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
10 y.o. car ~ $9,300 20 y.o. car ~ $2,200



4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
Due to the lack of a boundary for the function's domain some x values that extrapolate to infinity resulted in negative outputs. They amplify factors that depreciate the car's value, occaisionally beyond the point of logical reason. 
