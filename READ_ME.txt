There are two Jupyter Notebooks enclosed in our submission.
The main notebook - Group Project - contains the code that forms a dataset on fleet size, 
fuel use and carbon emissions, adjusted for population.
The second notebook - Fuel_price_inflation_calculations contains the code that joins inflation
rates, fuel prices and exchange rates to produce a dataset of the quarterly
tax rate, crude price and retail pump price, adjusted for inflation.

The notebooks are not connected in any programming sense - they can be run in either order. 
We decided to keep them separate since the dataset produced by each felt naturally
self contained.


Datasets we created:

FuelCO2.csv - Contains a table created from two tables in the NZ vehicle fleet file. It contains data around fuel usage and CO2 emissions for the light vehicle fleet and heavy vehicle fleet. The units for NZ litres, On road min estimate and max fuel estimate are in millions of litres. The units for Light passenger, commercial and heavy fleet are in millions of tonnes (CO2 emissions).

FuelCO2New.csv - Contains a table which is a subset of the FuelCO2 table. We subsetted the CO2 emissions (millions of tonnes) data and used this to create our bar chart titled "CO2 emissions in each type of vehicle". The units for the emissions are in millions of tonnes

FuelCO2NewUpdate.csv - Contains a table which is a subset of the fuelCO2pop_per table.......

fleet_population.csv - 

fleet_size.csv - 

population_new.csv - Contains a table which is a subset of the population table. It contains the Year of the recorded population the total population and the average total population.

update.csv - 

Quarterly_fuel_price_real_and_nominal - A dataset we produced of quarterly figures related to fuel prices in both nominal and real terms (before and after inflation is taken into consideration). This includes discounted petrol price, in cents per litre, barrel price in USD and in NZD, fuel tax (including GST), and crude oil price converted into cents per litre ($NZD) . Discounted petrol price is the price paid by consumers at the pump after the average retail discount (from supemarket discounts) is taken into account. These figures, including the USD/NZD exchange rate are averages for each quarter.







