# Assignment
  
#### Making coffee using a drip coffee machine

# Assumptions

1. Drip coffee machine
2. Using pre ground coffee beans 
3. Using paper coffee filters 
4. Water is easily accessible and can be inserted to the machine easily
5. The coffee maker opens up to be able to insert contents
6. Two buttons to start brew and set brew time

# Variables
```
Coffee machine - the main device in the process
Filter - the filter that is inserted into the grounds container before the grounds
Grounds - the coffee beans themselves that are preground
Water - water already in a container ready to be inserted into the coffee machine
Water reservoir in coffee machine
Filter container in coffee machine
Desired time - the set time at which coffee machine will auto brew the coffee if all contents are inside
```

# Pseudocode

```js
BEGIN

FUNCTION open coffee machine
  CHECK water reservior
    IF water resorvoir = EMPTY
      ADD water => water resorvoir
        FILL water to WATER AMOUNT
          WATER AMOUNT = (x)
      
FUNCTION filter check
  CHECK filter container
    IF filter container contains no filter
      GRAB filter 
        ADD filter => filter container
    ELSE
      RUN FUNCTION pour grounds 
        
FUNCTION pour grounds
  GRAB grounds 
    FILL filter container with GROUNDS AMOUNT
      GROUNDS AMOUNT = (i)
    POUR grounds => filter container

FUNCTION set time 
  IF no time inserted
    RUN brew coffee
  ELSE input DESIRED TIME
    DESIRED TIME = ("0:00")
      RUN FUNCTION push button
      
FUNCTION brew coffee
  IF DESIRED TIME = undefined
    BREW COFFEE immediately
  ELSE 
    BREW COFFEE = DESIRED TIME
```
### Enjoy coffee!



      
      
    

    





