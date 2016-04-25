
# Drink up

We've been watching how much three people drink for three days. For Science! We've got some data, and now we need to make some calculations.

## The Data

```javascript
var Monday = [
   {
       "name": "Mdu",
       "coffee": 5
       "tea": 0
       "water": 3
   },
   {
       "name": "Brenda",
       "coffee": 1
       "tea": 3
       "water": 1
   }
   {
       "name": "Lesego",
       "coffee": 0
       "tea": 4
       "water": 2
   }
];

var Tuesday = [
   {
       "name": "Lesego",
       "coffee": 1
       "tea": 3
       "water": 1
   },
   {
       "name": "Mdu",
       "coffee": 7
       "tea": 0
       "water": 5
   },
   {
       "name": "Brenda",
       "coffee": 2
       "tea": 4
       "water": 0
   }
];

var Wednesday = [
   {
       "name": "Brenda",
       "coffee": 3
       "tea": 2
       "water": 4
   },
   {
       "name": "Lesego",
       "coffee": 0
       "tea": 3
       "water": 4
   },
   {
       "name": "Mdu",
       "coffee": 8
       "tea": 2
       "water": 9
   }
];
```

## The Quest

Use TDD and write code to answer the following questions.

### How much?

* How many coffees were drunk on Monday?
* How many teas were drunk on Monday?
* How many waters were drunk on Monday?

### Who?

* Who drank the least coffee on Monday?
* Who drank the most tea on Tuesday?
* Who drank the least water on Wednesday?

### All Week Long

* How many coffees did Lesego drink during the whole week?
* How many teas did Brenda drink during the whole week?
* How many waters did Mdu drink during the whole week?
* Who drank the most coffee during the whole week?
* Who drank the least tea during the whole week?
* Who drank the most water during the whole week?

## The Sequel

The Science People were impressed with our calculations and have sent us some more data. They sent it via carrier pigeon, then fax, which was typed out and emailed to us. The data was for Thursday:

> "So this is Thursday, hey. Mdu went off on one and had 12 coffees, 10 waters, and 1 tea. Lesego had 2 teas, 2 coffees, and 2 waters. Brenda had 4 waters, 5 coffees, and 6 teas."

Use string functions to make a new map of this data, then answer the questions below.


### All Week Long

* How many coffees did Mdu drink during all four days?
* How many teas did Brenda drink during all four days?
* How many waters did Lesego drink during all four days?
* Who drank the most coffee during all four days?
* Who drank the least tea during all four days?
* Who drank the most water during all four days?
