# sales_prediction
# Overview
For companies to become competitive and skyrocket their growth, they need to leverage Al/ ML to develop predictive models to forecast sales in the future. Predictive models attempt at forecasting future sales based on historical data while taking into account seasonality effects, demand, holidays, promotions, and competition.
## Objective
The objective of project is to predict future daily sales based on historical data. 
## Features
* 1115 unique stores
* *Note that sales is the target variable (that's what we are trying to predict)*
* Id: transaction ID (combination of Store and date)
* Store: unique store Id
* Sales: sales/day, this is the target variable
* Customers: number of customers on a given day
* Open: Boolean to say whether a store is open or closed (0 = closed, 1 = open)
* Promo: describes if store is running a promo on that day or not
* StateHoliday: indicate which state holiday (a = public holiday, b = Easter holiday, c = Christmas, 0 = None)
* SchoolHoliday: indicates if the (Store, Date) was affected by the closure of public schools
* StoreType: categorical variable to indicate type of store (a, b, c, d)
* Assortment: describes an assortment level: a = basic, b = extra, c = extended
* CompetitionDistance (meters): distance to closest competitor store
* CompetitionOpenSince [Month/Year]: provides an estimate of the date when competition was open
* Promo2: Promo2 is a continuing and consecutive promotion for some stores (0 = store is not participating, 1 = store is participating)
* Promo2Since [Year/Week]: date when the store started participating in Promo2
* PromoInterval: describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew.
## Used algorithm
https://pypi.org/project/fbprophet/
