# Project Diary  

### Log #01 2017-07-25 01:26EST  

Starting the second project for The Lede 2017. I will be exploring the proximity of fast food restaurants to schools in New York City, and how that correlates with youth obesity rates.  

NYC is actually not really known for having an obesity problem, rather a lot of people seem to be excercising, so I might have to shift focus on a state or city that has a more sizeable obesity problem.

For the time being I'm building store locations for NYC, and will see how it goes.

### Log #02 2017-05-29 13:33EST

I realised that the data I have downloaded, concern Adult Obesity Rates and not Youth Obesity Rates.
I will have to go back to the NYC Data Portal and look for the Youth Obesity Rates.

Progress so far:
Mined store locations for 7 fast food restaurant chains, and joined them with schools and UHF34 neighborhoods geometries.
With vincenty module I am able to look for number of restaurants in any given radius from every school.

Attention:
I need to revise, determine and make clear my methodology for calculating how many restaurants are close to each school, because the longer the radius is, the more restaurants are over-lapping with each other, and I'm getting potentially inaccurate results. For example, a radius of 0.1 miles around each school yiels ~380 results for restaurants, while a radius of 0.5 around schools is yielding <10,000 results for restaurants.

Also, I should calculate an average of number of restaurants close to schools, or absolute numbers? Absolute numbers are inaccurate because of overlapping?