# Housing
A predictive model for home prices in Sacramento

## Exploratory analysis summary
1. In Sacramento city, the expensive houses are mainly located on the northwest side and the center of the city. there are still some on the east side and southeast side. However, for houses outside of Sacramento, the distribution of expensive houses is more sparse
The overall price is much higher on May 15 than other dates. For the other dates, there are still some expensive houses sold but most of them are not that expensive.
2. Housing is quite different for Sacramento and otheres. Houses are generally larger than 750 sq__ft but many houses are between 500 and 750 in Sacramento. Also, most of houses are cheaper than 400,000 while there are many houses have prices between 400,000 and 800,000 in other cities. Another thing is that in Sacramento, there are much more houses under 200,000 than other cities.
3. The overall housing price is cheaper in Sacramento than other cities in all kinds of streets. Especially for PL, the average price increases by around 250,000 and those most expensive houses (over 800,000) are all located in other cities

## Machine learning models performance

| Model  |  Cross Validation MSE	 | Test MSE |
| ------------- | ------------- | ------------- |
| Baseline	  |    14311627419.02095   |
| Ridge	     |     5357328970.21	   |   5837489353.82  |
| Decision Tree |	6507204205.87	   |   7907573268.44 |
| Random Forest	|  5532697156.03	  |    6610555583.08 |
