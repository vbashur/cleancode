# cleancode

## References for clean code workshop


## Contents

### Session 1
* Importance of clean code
* Best practices: SOLID DRY KISS etc
* Name conventions
* Formatting
* Importance of tests
* 4 creiterias that proves your code quality

### Session 2
* 6 aspects of the bad project [https://ru.wikipedia.org/wiki/SOLID_(%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BD%D0%BE-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)]
* Single responsibility
* Open-closed
* Liskov substitution
* Interface segregation
* Dependency inversion

### Session 3
* Violations of code conventions (what happens when engineer ignores review remarks)
* Code conventions review
** formatting
** naming
** (https://github.com/softwaresaved/clean-code-workshop/blob/master/README.md)


Naming
Code sample:
public int index;
public List<int[]> itemList;
public List<int[]> getItems() {
    List<int[]> list1 = new ArrayList<int[]>();
    for (int[] x : itemList) 
        if (x[index] == 4)
            list1.add(x);
    return list1;    
}

1	1	1	1	1
1	4	2	2	4
1	3	4	2	1
4	2	1	2	1
1	1	0	1	4


What is the itemList ?
What is index?
Why x[index] is important?
What is 4?
How are we going to use returned list?

Hint: minesweeper
