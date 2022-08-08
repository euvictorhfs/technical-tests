# Infinite Coins

:warning: Before viewing each of my codes, please check my personal notes to understand my learning methodology. This work is not a final project and aims at a continuous improvement of my own learning in all requested languages.

---

See my personal notes (in Portuguese) on GitHub at [algorithmSolutions.md](algorithmSolutions.md).

---

Given an infinite number of quarters (25 cents), dimes (10 cents), nickels (5 cents) and pennies (1 cent), write a method <code>**makeChange()**</code> to calculate and return a Set containing the ways of representing n cents using those coins. Each element of the returned Set should represent the number of coins to compose the entry value, an array like this: [quarters, dimes, nickels, pennies].

The method <code>**makeChange()**</code> can use a Set data structure to store each representation of n cents, and then, return it. A **Set** is a collection that contains no duplicate elements and the order of elements is irrelevant. Consider the following interface defined for Set:

| Method Signature              | Method Description                                           |
| ----------------------------- | ------------------------------------------------------------ |
| boolean add (Element e)       | Adds the specified element to this set if it is not already present (optional operation). |
| boolean addAll (Set s)        | Adds all elements from that are not already present in this set. |
| boolean contains (Element e)  | Returns true if this set contains the specified element.     |
| boolean equals (Sets s)       | Compares the specified set with this set for equality.       |
| Iterator <Element> iterator() | Returns an iterator over the elements in this set.           |
| boolean remove (Element e)    | Removes the specified element from this set if it is present (optional operation). |
| int size()                    | Returns the number of elements in this set (its cardinality). |
| Element[] toArray()           | Returns an array containing all of the elements in this set. |

<p align="center">
    <i>Table: Set interface</i>
</p>

**Input example:**

​	<code>n=12</code>

Output for the given example:

​	<code>[[0,0,0,12], [0,0,1,7], [0,0,2,2], [0,1,0,2]]*</code>

	* this is the content of the **Set** which should be returned by the function.

Your proposed solution can be written in **pseudo-code** or any well-known language (C, C++, Java, etc) and you are free to implement any auxiliary functions. Besides, write down a comment to the implemented function, explaining how your function will work like the one below.

```html
/**
* The function below will ...
* - Obtain the input
* - Iterate over the elements
* - ...
* - Print the output and return...
*/
```

:warning: The algorithm solution must be added to a gist repository (https://gist.github.com/) to avoid errors in interpretation and compilation, when applicable.

