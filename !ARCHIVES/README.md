


```
cd dataviz-project-template
npm install
```
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


##Visualization:
Here is a look at the final visualization:

![Prototype](images/Prototype.PNG)

Link to final visualization](https://robertdelgado.github.io/dataviz-project-template_rdelgado/)

The main (rightmost) graph shows both cumulative greenhouse gas emission by country for each year from 1990 to 2013.  When the user hovers over the top circle, the user will see the country's population and cumulative greenhouse
gas emissions as of 2013.

The smaller circles represent each of the previous years.  Their vertical displacement represents each country's cumulative greeenhouse gas emissions for that year.  When the user hovers over one of the smaller circles, the circle highlights
along with the interval between it and the circle representing the previous year (representing the annual greenhouse gas emissions for that country).  










[Previous Prototype](https://bl.ocks.org/RobertDelgado/f823d3683bb591bac643bfc7cf35d6a4/66fddccde67fac1c391a2a79634576d3577507a9)