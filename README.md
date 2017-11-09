
## Introduction:

Few would argue against the existance of global warming.  From land/sea surface temperature increases to glacial melting and loss of northern snow cover, the evidence has been compelling, (https://climate.nasa.gov/evidence/).
Despite this apparent truth, many would argue about the role that human beings play in global warming.  
Some argue that recent temperature increases are due to the earth's natural climate cycle, or that there is no consensus in the scientific community that global warming is caused by human beings.
(https://www.skepticalscience.com/argument.php) .  Regardless of one's political or ideological tendencies, the majority of the scientific community agrees that human beings have played a large part in global warming.  
Greenhouse gasses are thought to be the major enabler of the greenhouse effect.  Greenhouse gasses include Carbon dioxide, Methane, Nitrus Oxide and Water vapor.  Greenhouse gases are emitted by vehicles, power production plants, industry and 
even in agricultural processes.  The visualizations presented in this article are meant to show the recent greenhouse emission trends among the top 10 greenhouse emitting countries.

## Data:

The data behind the visualization is from the following source:


Link: (http://www.wri.org/resources/data-sets/cait-country-greenhouse-gas-emissions-data)

The data includes: 

1.	 Annual GHG emissions by country (with breakout by GHG class, not used)

2.	Population of said country in year

3.	GDP by year by country (not used).

## Tasks:

The questions to guide this visualization are as follows:

a.	How much greenhouse gas did each country emit in each year

b.	How much greenhouse gas did each country emit since 1990.  

c.	Would also like a feel for each country’s population.

d. (If I have time), Which countries are the most wasteful?  In other words, which countries had the greatest greenhouse gas emission per person?  Did this change over time?


## Visualization:
Here is a look at the final visualization:

[Link to final visualization](https://robertdelgado.github.io/dataviz-project-template_rdelgado/)

The main (rightmost) graph shows both cumulative greenhouse gas emission by country for each year from 1990 to 2013.  When the user hovers over the top circle, the user will see the country's population and cumulative greenhouse
gas emissions as of 2013.

The smaller circles represent each of the previous years.  Their vertical displacement represents each country's cumulative greeenhouse gas emissions for that year.  When the user hovers over one of the smaller circles, the 
circle representing that year highlights along with the interval between it and the circle representing the previous year *for each country*.  Furthermore the appropriate intervals and marks highlight on the 2 secondary 
graphs (that will be explained).

The other two graphs, to the right show the annual greenhouse gas emission level and greenhouse gas emissions per capita for each of the countries.  The interactions are similar to those with the main graph.

## Previous attempts:
The final idiom is a result of alot of trial and error:

I first wanted to allow the user to pan across a set of tiled scatter-plots.  However when I saw the data, found that this would be very wasteful and clumsy.  Here is a sample of data for 2012:
[Link to first prototype](https://bl.ocks.org/RobertDelgado/a5eb4532c2dd3a564cca012d985b5fef/14055ce319ae5e0a88628a813455a08d35b810a1)
	
After a bit of thought, I settled on the form for the main graph.  However, I still wanted to tile the graphs to allow the user simultaneous access to each of the graphs.  This might have worked with say 6 years but with 
24 years, (1990 to 2013), panning and zooming was overwhelming.  As a user, I got lost very easily and spent more energy keeping track of where I was than digesting the vis contents.  

[Link](https://bl.ocks.org/RobertDelgado/f823d3683bb591bac643bfc7cf35d6a4/66fddccde67fac1c391a2a79634576d3577507a9) 
This was clearly unacceptable so... back to the drawing board.

I finally settled on the final form and decided to use interaction to convey the detailed informatiion.  Yes. "Details on Demand".

## Conclusion:
I hope that you enjoy this visualiztion as much as I enjoyed creating it.  Thank you. :)








