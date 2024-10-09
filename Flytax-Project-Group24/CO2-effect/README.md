# CO2-emissions folder
Avia-par csv file contains the Passengers between each airport in the Netherlands and other airports
Herefrom, the quantity of passengers to/from each location is retrieved
Also, this file gives the flight location. Herewith, together with other libraries, we calculate the traveldistance (usiing geopy library and airport data)
Now, we know how many passengers travel what amount of kilometers
Then, in an external file, the emission factor for different kind of flights is given (3 categories), and these get multiplied by the amount of kilometres per passenger.
Eventually, we can make a file with emissions per flight route based on the total quantity of passengers