# Collection & Data Structures basics

### System.Collections & System.Collections.Generic

    2 types of collections 
    - Generic - [type-safe at compile time] [better performance]
    - Non-generic [require casting]

### System.Collections.Concurrent
    Offer thread safe operations for accessing collections from multiple threads

### System.Collections.Immutable
    Inherently thread safe because they are operating on the original copy of the collections

# Features of a collection
    - All collections are enumeratable with foreach, in or for each..next statement
    - All collections can be copied in to an array [1D]
    - Many collections have capacity (number of elements it can contain) & count (number of elements it contains)
    - Most collections automatically expand in capacity when current capacity is reached. Memory is reallocated -> old collection is copied into new collection -> [But negatively affects performance]
    - Lower bounds of a collection is always 0

# Choosing collections and its complexity 
| Use | Generic | Non-generic | 
| --- | ----------- | -------- |
| Key-Value pair | Dictionary<Key, Value> | Hashtable | 
| Access items by index|List<T>|Array (fixed capacity), ArrayList (automatically expandable) |
| FIFO | Queue<T> | Queue |
| LIFO | Stack<T> | Stack |
| Access Items sequentially | LinkedList<T> | None|
| Sorted collection | SortedList<T> | SortedList | 
| Set (No order, no duplication) | HashSet<T>, SortedSet<T> | none | 

# Algorithemic Complexity of Collections [In Progress]

| Collection | Add | Remove | Enumerate (sorted, non sorted) | Search | Allow duplicates | 
| ---| ---| ---| --- | --- | --- |
| Stack | | | | |
| Queue | | | | |
| List | | | | |
| HashSet | | | | |
| SortedSet | | | | | 
| Dictionary | | | | |
| SortedDictionary | | | | | 













