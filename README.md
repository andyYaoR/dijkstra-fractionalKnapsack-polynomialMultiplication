# PAA 2017-1

The purpose of this project is to solve the list of problem 1.


### How to run

```
./trabalho <instance_path> <question>
```

where:
* Question **1a** is the dijkstra algorithm implemented with array
* Question **1b** is the dijkstra algorithm implemented with AVL tree
* Question **1c** is the dijkstra algorithm implemented with fibonacci heap
* Question **1d** is the dijkstra algorithm implemented with buckets
* Question **1e** is the dijkstra algorithm implemented with alpha tree
* Question **2a** is the fractional knapsack problem - O(nlogn)
* Question **2b** is the fractional knapsack problem - O(n)
* Question **2c** is the fractional knapsack problem - O(nˆ2)
* Question **3a** is the polynomial multiplication - O(nˆ2)
* Question **3b** is the polynomial multiplication - O(nˆlog3)
* Question **3c** is the polynomial multiplication - O(nlogn)


**Example**
```
./trabalho path 2a
```


### Instance Format

**Input format to Question 2**

The input file should be in the following format:

```
NbItems
<< And then for each item >>
Index Profit Weight
KnapsackSize
```

**Output format to Question 2**

The output file should be in the following format:

```
NbItemsUsed TotalWeight TotalProfit
<< And then for each item placed in the knapsack >>
ItemIndex FractionOfItem
```

**Some remarks**
** The second field "FractionOfItem" belongs between [0,1].



