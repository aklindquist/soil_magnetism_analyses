# soil_magnetism_analyses
This contains jupyter notebooks for student use when analyzing magnetic data from soil sediments.

## Soil Magnetic Analyses  
These files were designed to clean and plot hysteresis loops, and magnetic properties with depth. 
The hysteresis loop files should remove the paramagnetic component and return the four primary hysteresis values: Hc, Hcr, Mr, Ms. 
It will also plot these on a Day plot (Day et al., 1977).

## Usage  
Files will need to be csv files with two columns, the applied field (often in T) and the magnetic moment of your sample (Am2).
A separate file can also be uploaded for the backfield measurements. These are required to calculate Hcr. 
The two hysteresis files run the same code - one as a large block to gather the data, a second in pieces to help you understand what is happening at each step.


