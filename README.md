_**#Aim :-**_ 
To study and implement Sets in Python and understand their properties, syntax, and basic operations such as adding, removing elements and performing set operations.

**#Theory :-**__
A set in Python is an unordered collection of unique elements. Sets are useful when duplicate values are not required and when mathematical set operations need to be performed.
Properties of Sets
-Sets are unordered.
-Duplicate elements are not allowed.
-Sets are mutable, i.e., elements can be added or removed.
-Boolean value True and integer 1 are treated as the same.
-Sets support mathematical operations like union and intersection.

**Syntax for Creating a Set**
set_name = {element1, element2, element3}

**Membership Testing**
Used to check whether an element exists in a set using the in keyword.

**Adding and Removing Elements**
- add() :is used to insert an element. Syntax:- thisset.add("orange")
- remove() deletes an element (error if not found). Syntax:- thisset.remove("banana")
- discard() deletes an element without error
  
**Set Operation**
- Union (|)
- Intersection (&)
- Difference (-)
- Symmetric Difference (^)

**Frozen Set**
- A frozenset is an immutable version of a set, meaning its elements cannot be changed once created.
syntax :- frozenset(iterable)

_**#Algorithm**_
1. Start the program.
2. Create a set using {} with required elements.
3. Display the set using print().
4. Check whether an element exists using the in keyword.
5. Add elements to the set using add() and remove elements using remove() or discard().
6. Perform set operations such as union (|), intersection (&), and difference (-).
7. Create a frozenset() to demonstrate immutability.
8. Display the final output and stop the program.

**Conclusion**
In this experiment, we studied the concept of sets in Python and their properties. We learned how sets store unique elements, how to perform basic operations, and how they help in efficient data handling. Sets are very useful for solving problems involving uniqueness and comparisons.
