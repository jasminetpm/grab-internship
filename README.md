# grab-internship
Product Analytics Internship in Grab

## Brief
In the summer of 2018, I interned in Grab, Southeast Asia's leading ride-hailing app. Working in the Product Analytics Department, I delved into passenger and driver data from the months of May and June-- creating data visualizations for two projects: 
1. Book-Through Rate of Grab Trips vs Public Transport
2. Mispriced Trips
Then, I carried out analyses based these data visualizations, which subsequently led to solutions proposed to improve current problems faced by Grab.

## Book-Through Rate of Grab Trips vs Public Transport
The aim of this project was to find out the relationship between Book-Through Rate (BTR) of Grab Trips and their Grab-to-Public-Transport-Time Ratio. Our hypothesis was that BTR increases as Grab-to-Public-Transport Time Ratio decreases (this means that the Grab trip takes way less time than public transport for the same journey). In other words, we hypothesized that BTR increases as time saved increases. Consequently, we found that this correlation was true only for peak hours (morning and evening peak) and night time, which means that people value time saved a lot more during peak hours and night time. However, there is little to no correlation for non-peak hours. This has implications and further improvements that could be made to Grab's pricing algorithm.

Then, I divided the data further, based on Surge and Distance for all the Grab trips in the dataset. Specifically, I wanted to find out if the BTR trend was different for passengers who paid a higher amount of Surge, compared to passengers with who didn't have to pay for Surge; as well as if the BTR trend differed for Grab trips of different distances. The conclusion was that BTR was strongly correlated to time saved for peak hours but not for all other hours. For non-peak hours, BTR was only strongly correlated for the trips that fell in the **high** surge bucket. The passengers who fall in the high-surge bucket are relatively  more price inelastic and highly likely to book a Grab ride when the Grab trip saves more time than public transport. Again, this has implications and further work that could be proposed for Grab's pricing.

## Mispriced Trips
The aim of this project was to find out if there were Grab trips that could be better priced, based on passenger (pax) and idle driver (dax) data. There were two conclusions drawn from this project and its analyses. 

Firstly, the data visualizations showed patterns of idle Grab drivers lingering outside the Central Business District (CBD) area from 7pm onwards, despite there being a high demand for Grab rides inside the CBD. We realised that although there were little idle drivers around the CBD at the start of peak hour (6pm), idle drivers started appearing in the hours after. This is most probably due to the Electronic Road Pricing (ERP) surcharge that is imposed on cars entering the CBD during peak hours. Drivers are hence reluctant to enter the CBD to pick up passengers because they are not reimbursed for the ERP fee that they bear. As a result, a suggestion was proposed to allow drivers to transfer the cost of the ERP to passengers looking for rides in the CBD to encourage idle drivers to enter the CBD, in order to meet the high demand for Grab rides there during peak hours (especially evening peak).

Secondly, from the data visualizations, we realized that there were many idle drivers circling around the far-flung and relatively isolated areas of Jurong (Industrial Area) and Changi (Army Ferry Terminal) during morning peak hours. This could be because many passengers book Grab rides to these areas, which are not well-served by public transport. However, these drivers are not being re-allocated to areas with high demand after their trips to the far-flung areas. This prompted us to question if Grab's driver allocation algorithm could be improved or if surcharges could be imposed on passengers who book Grab rides to far-flung locations that would pull drivers away from central locations that have high demand at peak hour.