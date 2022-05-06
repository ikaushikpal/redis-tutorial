# redis tutorial
![redis-image](images/redis.jpg)
___
<p style="color:white;background-color:black;text-align:center">KAUSHIK</p>

___
<p style="color:white;background-color:grey;text-align:center">AMIT</p>

___
<p style="color:white;background-color:black;text-align:center">SUPRIYO</p>

### string
 - Set key name with value:
    > set **key** **val**

 - set multiple key-value pair:
    >mset **key1** **val1** **key2** **val2** ... 

 - setnx (uses for declare key if not existed before)
    > setnx **key** **val**

 - set key with expiry in seconds:
    > setex **key** **time_in_seconds** **val**

 - set key with expiry in milliseconds:
    > psetex **key** **time_in_milliseconds** **val**

 - get time-to-leave for a key set with time-expiry in seconds:
    > ttl **key**

 - Get variable name with key/variable:
    > get **key**

 - get all key stored:
    > keys *

 - delete a key:
    > del **key**

 - delete all keys:
    > flushall

 - clear the terminal:
    > clear 

 - Increment/Decrement of key value by 1 in case of integer value:
    >incr **key**
    > decr **key**

 - Increment/Decrement of key value by n in case of integer value:
    > incrby **key** **n**
    > decrby **key** **n**

 - Append string with another key value:
    > append **key** **string**

 - Get length of a key value:
    > strlen **key**

### set
(No repetition is allowed, it is a unordered set)

- Create or add element in set if the set do not exists:
    > sadd **a_set** **val1 val2 val3**

- Display all elements of a set
    > smembers **a_set**

- Get number of elements in a set:
    > scard **a_set**

- Get difference between two sets:
    >sdiff **a_set** **another_set** 
    (equivalent to set operation: a_set - another_set)

    > sdiffstore **new_set** **a_set** **another_set**
    (stores the difference between a_set and another_set in new_set)

- Union of two sets:
    > sunion **a_set** **another_set**
    (equivalent to set operation a_set ∪ another_set)

    > sunionstore **new_set** **a_set** **another_set**
    (union of a_set and another_set will be store in new_set)

- Intersection of two sets:
    > sinter **a_set** **another_set**
    (equivalent to set operation a_set ∩ another_set)

    > sinterstore **new_set** **a_set** **another_set**
    (intersection of a_set and another_set will be store in new_set)
 
- Remove element from set:
    > srem **a_set val1 val2 ...**

- For any random deletion of n element:
    > spop **a_set n**

- Move element between two set:
    > smove **a_set another_set val**
    (This moves val from a_set to another_set)


### ordered set

- 


___
# interview questions
Source 1: [javatpoint](https://www.javatpoint.com/redis-interview-questions-and-answers)

Source 2: [Medium](https://medium.com/@cosmicconvallis/interview-questions-on-redis-for-developers-c27769b410e9)

Source 3: [guru99](https://career.guru99.com/top-10-redis-interview-questions/)