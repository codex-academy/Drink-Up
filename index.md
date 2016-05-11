---
layout: default
title: Drink Up
---

# Drink up

We've been watching how much three people drink for three days. For Science! We've got some data, and now we need to make some calculations.

## The Data

```javascript
var Monday = [
   {
       "person": "Mdu",
       "coffee": 5,
       "tea": 0,
       "water": 3
   },
   {
       "person": "Brenda",
       "coffee": 1,
       "tea": 3,
       "water": 1
   },
   {
       "person": "Lesego",
       "coffee": 0,
       "tea": 4,
       "water": 2
   }
];

var Tuesday = [
   {
       "person": "Lesego",
       "tea": 3,
       "water": 1,
       "coffee": 1
   },
   {
       "person": "Mdu",
       "tea": 0,
       "water": 5,
       "coffee": 7
   },
   {
       "person": "Brenda",
       "tea": 4,
       "water": 0,
       "coffee": 2
   }
];

var Wednesday = [
   {
       "person": "Brenda",
       "water": 4,
       "coffee": 3,
       "tea": 2
   },
   {
       "person": "Lesego",
       "water": 4,
       "coffee": 0,
       "tea": 3
   },
   {
       "person": "Mdu",
       "water": 9,
       "coffee": 8,
       "tea": 2
   }
];
```

## The Quest

Use TDD and write code to answer the following questions.

### How much?

Write one function that answers these three questions.

* How many coffees were drunk on Monday?
* How many teas were drunk on Tuesday?
* How many waters were drunk on Wednesday?

### Who?

Write new function(s) that answer these three questions.

* Who drank the least coffee on Monday?
* Who drank the most tea on Tuesday?
* Who drank the least water on Wednesday?

### How much for a person?

* How many coffees did Lesego drink on Monday?
* How many teas did Brenda drink on Tuesday?
* How many waters did Mdu drink on Wednesday?

## The Sequel: Thursday

The Science People were impressed with our calculations and have sent us some more data. They sent it via carrier pigeon, then fax, which was typed out and emailed to us. The data was for Thursday:

```javascript
var Thursday = [
  {
      "person": "Mdu",
      "tea": 0,
      "coffee": 5,
      "water": 3
  },
  {
      "person": "Brenda",
      "coffee": 1,
      "water": 1,
      "tea": 3
  },
  {
      "person": "Lesego",
      "water": 2,
      "coffee": 0,
      "tea": 4
  }
];
```

Write some new tests, but **no new functions**, to check that your code answers the following questions correctly.

* How many coffees were drunk on Thursday?
* How many teas were drunk on Thursday?
* How many waters were drunk on Thursday?
* Who drank the least coffee on Thursday?
* Who drank the most tea on Thursday?
* Who drank the least water on Thursday?

---

## Extra Stuff

## The Sequel Sequel: Friday

The Science People have sent one last data burst: Friday.

```javascript
var Friday = [
  {
      "person": "Brenda",
      "tea": 3,
      "coffee": 1,
      "water": 1
  },
  {
      "person": "Lesego",
      "tea": 4,
      "water": 2,
      "coffee": 0
  },
  {
      "person": "Mdu",
      "water": 3,
      "tea": 0,
      "coffee": 5
  }
];
```

* How many coffees did Mdu drink during all five days?
* How many teas did Brenda drink during all five days?
* How many waters did Lesego drink during all five days?
* Who drank the most coffee during all five days?
* Who drank the least tea during all five days?
* Who drank the most water during all five days?
