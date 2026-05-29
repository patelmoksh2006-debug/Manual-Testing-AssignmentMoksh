PART A — Test Case Design Techniques



Assignment 1: Equivalence Partitioning (EP)



Requirement 1: Online Movie Ticket Booking App

Valid Class: 1>10

Invalid Class: >1

Invalid class: <10



|Test Data|Valid/Invalid Class|Expected Result|
|-|-|-|
|5|Valid|Ticket booked Successfully|
|0|Invalid|Less then the Booking limit|
|12|Invalid|More then the Booking limit|





Requirement 2 — Food Delivery App



Valid Class: 500>5000

Invalid Class: >500

Invalid class: <5000

|Test Data|Valid/Invalid Class|Expected Result|
|-|-|-|
|505|Valid|Coupon applied Successfully|
|495|Invalid|Less then the Coupon limit|
|5100|Invalid|More then the Coupon limit|





Requirement 3 — Mobile Recharge

Valid Class: 10>3000

Invalid Class: >10

Invalid class: <3000

|Test Data|Valid/Invalid Class|Expected Result|
|-|-|-|
|100|Valid|Mobile Recharge Successfully|
|5|Invalid|Mobile Recharge Unsuccessfully|
|3100|Invalid|Mobile Recharge Unsuccessfully|

&#x09;



Assignment 2: Boundary Value Analysis (BVA)

E-Commerce Website Password Length



Requirement 1:

Password length should be:



|Input|Expected Result|
|-|-|
|7|Less then the Minimum password length|
|8|password Successfully|
|9|password Successfully|
|14|password Successfully|
|15|password Successfully|
|16|More then the Maximum password length|

&#x09;



Requirement 2 — Flight Booking Age



|Input|Expected Result|
|-|-|
|1|Less then the minimum age|
|2|Booked Successfully|
|3|Booked Successfully|
|59|Booked Successfully|
|60|Booked Successfully|
|61|More then the Maximum age|





Requirement 3 — Internet Banking Transfer



|Input|Expected Result|
|-|-|
|0|Amount is More then the limit|
|1|Amount Successfully|
|2|Amount Successfully|
|99999|Amount Successfully|
|100000|Amount Successfully|
|100001|Amount is More then the limit|



**Requirement** 4 — Parking System



|Input|Expected Result|
|-|-|
|0|below the minimum range|
|1|parking system successfully|
|2|Parking System Successfully|
|23|Parking System Successfully|
|24|Parking System Successfully|
|25|Above the Maximum range |



###### Assignment 3: Decision Table Testing



Online Shopping Discount System

**Requirement** 1:



|Condition|Result 1|Result 2|Result 3|
|-|-|-|-|
| Premium member + Purchase > ₹5000|Yes|Yes||
|Premium member + Purchase < ₹5000|Yes|No||
|Non-premium + Purchase > ₹5000|No|Yes||
|Non-premium + Purchase < ₹5000|No|No||



