# ETLproject

EXTRACT<br>
We had some data bases in CSV file from the sales of Mercado Libre in Mexico City during 2018.<br>
We converted the CSV into Pandas Data Frame

TRANSFORM<br>
We changed the columns name for names that make sense to everyone and not only for people that works in Mercado Libre and understand their slang.<br>
We removed columns that were not necessary if we wanted to analyze the total sales by category and seller.<br>
For analysis purposes, we considered only the products which status were "active" (in file "Productos").

LOAD<br>
Finally, we send the different tables into MySQL in which we can make further analysis.
