# My Four Favorite Ruby Methods

### zero?
Returns a true boolean if the float returns 0 otherwise it returns false
```0.0.zero?``` #=> true
```3.829.zero?``` #=> false


### next_year
Called on a ruby date object and returns that date 1 year in the future.
```Date.new(2014, 8, 9).next_year``` #=> #<Date: 2015-08-09>

### .nil?
This method can be called on any ruby object and returns a boolean if that object is nil or not.
```"string".nil?``` #=> false
```0.nil?```  #=> false
```Object.new.nil?``` #=> false
```nil.nil?``` #=> true
```variable = nil``` 
 ```variable.nil?``` #=> true

### `map`
Transform every element in a collection and return a new array with results
```numbers = [1, 2, 3, 4, 5]``` 
 ```squared = numbers.map{ |num | num**2 }``` #=> [1, 4, 9, 16 , 25]
 

