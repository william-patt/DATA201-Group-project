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

fleet_size.csv - Contain a table which is a subset table of NZ vehicle fleet file. It was created by selecting and renaming varaibles (Period, Light_passenger,Light_commercial,Truck, Bus, Other, Total_vehicles, Light_passenger_increasing_rate, Light_commercial_increasing_rate, Trucks_increasing_rate, Bus_increasing_rate, Overall_increasing_rate, Light_passenger_per_thousand, Light_commercial_per_thousand) from the raw file.

population_new.csv - Contains a table which is a subset of the population table. It contains the Year of the recorded population the total population and the average total population.

fleet_population.csv - Contain a table create from joinning fleet_size and population_new.

FuelCO2.csv - Contains a table created from two tables in the NZ vehicle fleet file. It contains data around fuel usage and CO2 emissions for the light vehicle fleet and heavy vehicle fleet. The units for NZ litres, On road min estimate and max fuel estimate are in millions of litres. The units for Light passenger, commercial and heavy fleet are in millions of tonnes (CO2 emissions).

FuelCO2pop.csv - Contain a table create from joinning FuelCO2 and population_new.

FuelCO2New.csv - Contains a table which is a subset of the FuelCO2 table. We subsetted the CO2 emissions (millions of tonnes) data and used this to create our bar chart titled "CO2 emissions in each type of vehicle". The units for the emissions are in millions of tonnes

FuelCO2NewUpdate.csv - Contains a table which is wide format of FuelCO2New.

fuelCO2pop_per.csv - Contain a table create from joinning FuelCO2NewUpdate and population_new.

update.csv - Contain a table from the fuelCO2pop_per table with muating a new varible by value divided by Year_average_total and change unit of value (NZ_million_litres) instead of litres.

crash_data.csv - Contain a table form section1-historical-web file. And it used a Hundred thousand as unit of populations in pople and ten thousand as unit of population in vehicle.

Quarterly_fuel_price_real_and_nominal - A dataset we produced of quarterly figures related to fuel prices in both nominal and real terms (before and after inflation is taken into consideration). This includes discounted petrol price, in cents per litre, barrel price in USD and in NZD, fuel tax (including GST), and crude oil price converted into cents per litre ($NZD) . Discounted petrol price is the price paid by consumers at the pump after the average retail discount (from supemarket discounts) is taken into account. These figures, including the USD/NZD exchange rate are averages for each quarter.







