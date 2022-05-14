# Houseprices
Midtermproject for Ironhack Bootcamp Data Analytics

This is the midterm project.

Participators:

    - Christoph Rendel (@CrisQueCris)
    - Elizabeth Shogbanmu(Beth-sho)

The aim of this project is to identify factors that influence house prices. 
The basis for this study is a dataset of 21597 houses in King County of Washington state. 
    Wikipedia: 
    
        - King county has a population of 2 269 675 (census 2020) (most populated in Washington)
        - county seat is Seattle (pop: 737 015)
        - 5980 sqaure kilometres
        - 490 square km water bodies
        - highest mountain: Mount Daniel 2 426 m
        
 
![Heatmap](Data/heatmapprice.jpeg) 



The dataframe contains the following columns:

    0.   Unnamed: 0     21597 non-null  int64  
    1.   id             21597 non-null  int64  
    2.   date           21597 non-null  object 
    3.   bedrooms       21597 non-null  int64  
    4.   bathrooms      21597 non-null  float64
    5.   sqft_living    21597 non-null  int64  
    6.   sqft_lot       21597 non-null  int64  
    7.   floors         21597 non-null  float64
    8.   waterfront     21597 non-null  int64 
    9.   view           21597 non-null  int64
    10.  condition      21597 non-null  int64
    11.  grade          21597 non-null  int64  
    12.  sqft_above     21597 non-null  int64 
    13.  sqft_basement  21597 non-null  int64  
    14.  yr_built       21597 non-null  int64 
    15.  yr_renovated   21597 non-null  int64 
    16.  zipcode        21597 non-null  int64  
    17.  lat            21597 non-null  float64
    18.  long           21597 non-null  float64
    19.  sqft_living15  21597 non-null  int64  
    20.  sqft_lot15     21597 non-null  int64  
    21.  price          21597 non-null  int64

Descriptive Statistics of a few numerical variables:


|            bedrooms	|    sqft_living	|    sqft_lot	 |   yr_built	    |   price    |
|-----------------------|-------------------|----------------|------------------|------------|
| count	    21597.000000|	21597.000000	|2.159700e+04	 |   21597.000000	|2.159700e+04|
| mean	    3.373200	|    2080.321850	|    1.509941e+04|	1970.999676	    |5.402966e+05|
| std	       0.926299	|    918.106125	    |4.141264e+04	 |29.375234	        |3.673681e+05|
|min	       1.000000	|    370.000000	    |5.200000e+02	 |1900.000000	    |7.800000e+04|
| 25%	       3.000000	|    1430.000000	|    5.040000e+03|	1951.000000	    |3.220000e+05|
|50%	       3.000000	|   1910.000000	    |7.618000e+03	 |1975.000000	    |4.500000e+05|
|75%	       4.000000	|   2550.000000	    |1.068500e+04	 |1997.000000	    |6.450000e+05|
|max	      33.000000	|  13540.000000	    |1.651359e+06	 |2015.000000	    |7.700000e+06|



----------------------------------------------------------------------------------------------

Content: 

- Fnaljupyter.jpytn : Jupyter Notebook containing the Cleaning, Transformation and Modelling
- Data: contains the Dataset as csv and some grafics
- Presentation: Presentation of results
- Get Traveldistance to Seattle City Center: Accesed Google Distance Matrix API to get information about the travel distance from each house to the city center of Seatle
