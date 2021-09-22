# Hash Tables

<br><hr>

## Resources

<!-- ## How can we ensure that an effect hook runs only once ❓ [📁]() -->

![Hash Tables](https://media.geeksforgeeks.org/wp-content/uploads/20210108180437/Chaining2.jpg)

<br><hr>
<br>

- **Hash**

  > A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose.

- **Buckets**

  > A bucket is what is contained in each index of the array of the hashtable. **Each index is a bucket** <br>
  > An index could potentially contain multiple key/value pairs if a collision occurs.

- **Collisions**
  > A collision is what happens when more than one key gets hashed to the same location of the hashtable.

### What is a Hashtable ❓

> **Hashtables** are a data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value.

- A hashtable traditionally is created from an array

> **a structure that can map keys to values**. _A hash table uses a hash function_ _to compute an index_, also called a hash code, _into an array of buckets_ or slots, from which the desired value can be found.

## Why do we use it ❓

- Hold unique values
- Dictionary
- Library

<br>

- In hashing, large keys are converted into small keys by using hash functions. The values are then stored in a data structure called hash table. The idea of hashing is to distribute entries (key/value pairs) uniformly across an array. Each element is assigned a key (converted key). By using that key you can access the element in O(1) time.

### Hashing is implemented in two steps:

1. An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.
2. The element is stored in the hash table where it can be quickly retrieved using hashed key.

   - hash = hashfunc(key)
   - index = hash % array_size

## Hash function

> A hash function is any function that can be used to map a data set of an arbitrary size to a data set of a fixed size, which falls into the hash table. The values returned by a hash function are called hash values, hash codes, hash sums, or simply hashes.

<br><hr>
<br>

[📁 Intro to Hash Tables ](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html) <br>

[🎥 what is a hash table?](https://www.youtube.com/watch?v=MfhjkfocRR0) <br>

[📁 basics of hash tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/) <br>

[📁 ]() <br>
