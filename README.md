# Effective Go

* Names in Go have semantic effect: if started with upper case, then it is visible to the outside, otherwise not.
* Getters do not need to named as 'get\*', but setter will need.
* Can not put opening braces of a control structure on the next line
* *break* and *continue* can take optional label to identify what to break or continue
* *if* and *switch* accept an optional initilization statement like *for*
* *switch* is very general which can for examples strings, it is equvalent to if-else-if-else
* when there is a *return* statement without further parameters, it still return the current values of named return parameter
* Go's defer statement schedules a function call (the deferred function) to be run immediately before the function executing the defer returns
* *make* creates slices, maps, and channels only, and it returns an initialized (not zeroed) value of type T (not *T).
* Arrays
..* Arrays are values. Assigning one array to another copies all the elements.
..* In particular, if you pass an array to a function, it will receive a copy of the array, not a pointer to it.
..* The size of an array is part of its type. The types [10]int and [20]int are distinct.
