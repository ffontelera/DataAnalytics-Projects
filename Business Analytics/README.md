# Yandex Business Analytics

### The purpose of this project is to analyze the business metrics of the company Yandex Afisha and to help optimize their marketing expenses

#### The following data are given: 
* Server logs with data on Yandex.Afisha visits from January 2017 through December 2018
* Dump file with all orders for the period
* Marketing expenses statistics

#### The objective of this project :
* How people use the product?
* When they start to buy?
* How much money each customer brings?
* When they pay off?

### Description of the data
The visits table (server logs with data on website visits):
* Uid — user's unique identifier
* Device — user's device
* Start Ts — session start date and time
* End Ts — session end date and time
* Source Id — identifier of the ad source the user came from

The orders table (data on orders):
* Uid — unique identifier of the user making an order
* Buy Ts — order date and time
* Revenue — Yandex.Afisha's revenue from the order

The costs table (data on marketing expenses):
* source_id — ad source identifier
* dt — date
* costs — expenses on this ad source on this day

#### Python libraries used: Pandas, Matplotlib, Seaborn, Scipy
