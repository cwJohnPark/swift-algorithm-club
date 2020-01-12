# 스위프트 알고리즘 클럽에 오신 것을 환영합니다!

이 저장소에서 당신은 알고리즘과 자료구조를 스위프트로 구현한 코드를 찾을 수 있습니다. 또한 어떻게 알고리즘과 자료구조가 동작하는지에 대한 자세한 설명을 볼 수 있습니다.

만약 당신이 컴퓨터 과학을 공부하는 학생이고 시험에 이러한 코드들이 필요하다면 (또는 당신이 이론을 공부하고 싶은 독학 프로그래머라면) 여기가 최적의 장소입니다!

이 프로젝트의 목표는 **알고리즘이 어떻게 동작하는지**에 대해 설명하는 것입니다. 또한, 이 프로젝트는 명확하고 가독성있는 코드에 집중하며 당신의 프로젝트에 곧바로 옮길 수 있는 재사용가능한 라이브러리를 만드는 것이 목적이 아닙니다. 즉, 대부분의 코드가 당신의 프로젝트에 사용될 수 있지만 그 프로젝트에 맞게 수정이 필요하다는 것입니다.

이 프로젝트의 코드는 **Xcode 10**과 **Swift 4.2**에 맞추어 작성되었습니다. 우리들은 스위프트의 최신버전의 업데이트에 맞추어 코드를 갱신할 것입니다. 깃헙 페이지에 관심이 있다면 여기를 참고하세요. [클릭](https://aquarchitect.github.io/swift-algorithm-club/).


## 중요 링크

[알고리즘과 자료구조란?](What%20are%20Algorithms.markdown) 팬케이크!

[왜 알고리즘을 배워야하나요?](Why%20Algorithms.markdown) 알고리즘이 당신의 흥미에 맞지 않아 걱정되신다면 그럼 이것을 읽어보세요.

[빅오 표기법, Big-O notation](Big-O%20Notation.markdown). 우리는 종종 이것을 "알고리즘은 **O(n)**.이다"라고 말합니다. 이해가 되지 않는다면 읽어보세요.

[알고리즘 디자인 기법](Algorithm%20Design.markdown). 어떻게 알고리즘을 만들까?

[이 프로젝트에 기여하는 법](https://github.com/raywenderlich/swift-algorithm-club/blob/master/.github/CONTRIBUTING.md). 피드백을 받기 위해서 이슈 리포트를 하시거나 풀 리퀘스트를 요청하세요.

## 어디서부터 시작할까요?

만약 당신이 알고리즘과 자료구조를 처음 접한다면 다음의 것들을 먼저 익혀보세요.

- [Stack, 스택](Stack/)
- [Queue, 큐](Queue/)
- [Insertion Sort, 삽입 정렬](Insertion%20Sort/)
- [Binary Search, 이진 탐색](Binary%20Search/) and [Binary Search Tree, 이진 탐색 트리](Binary%20Search%20Tree/)
- [Merge Sort, 합병 정렬](Merge%20Sort/)
- [Boyer-Moore string search, 보이어-무어 문자열 검색](Boyer-Moore-Horspool/)

## 알고리즘

### 검색

- [Linear Search](Linear%20Search/). Find an element in an array.
- [Binary Search](Binary%20Search/). Quickly find elements in a sorted array.
- [Count Occurrences](Count%20Occurrences/). Count how often a value appears in an array.
- [Select Minimum / Maximum](Select%20Minimum%20Maximum). Find the minimum/maximum value in an array.
- [k-th Largest Element](Kth%20Largest%20Element/). Find the *k*-th largest element in an array, such as the median.
- [Selection Sampling](Selection%20Sampling/). Randomly choose a bunch of items from a collection.
- [Union-Find](Union-Find/). Keeps track of disjoint sets and lets you quickly merge them.


### 문자열 검색

- [Brute-Force String Search](Brute-Force%20String%20Search/). A naive method.
- [Boyer-Moore](Boyer-Moore-Horspool/). A fast method to search for substrings. It skips ahead based on a look-up table, to avoid looking at every character in the text.
- [Knuth-Morris-Pratt](Knuth-Morris-Pratt/). A linear-time string algorithm that returns indexes of all occurrencies of a given pattern.
- [Rabin-Karp](Rabin-Karp/)  Faster search by using hashing.
- [Longest Common Subsequence](Longest%20Common%20Subsequence/). Find the longest sequence of characters that appear in the same order in both strings.
- [Z-Algorithm](Z-Algorithm/). Finds all instances of a pattern in a String, and returns the indexes of where the pattern starts within the String.

### 정렬

It's fun to see how sorting algorithms work, but in practice you'll almost never have to provide your own sorting routines. Swift's own `sort()` is more than up to the job. But if you're curious, read on...

Basic sorts:

- [Insertion Sort](Insertion%20Sort/)
- [Selection Sort](Selection%20Sort/)
- [Shell Sort](Shell%20Sort/)

Fast sorts:

- [Quicksort](Quicksort/)
- [Merge Sort](Merge%20Sort/)
- [Heap Sort](Heap%20Sort/)

Hybrid sorts:

- [Introsort](Introsort/)

Special-purpose sorts:

- [Counting Sort](Counting%20Sort/)
- [Radix Sort](Radix%20Sort/)
- [Topological Sort](Topological%20Sort/)

Bad sorting algorithms (don't use these!):

- [Bubble Sort](Bubble%20Sort/)
- [Slow Sort](Slow%20Sort/)

### 압축

- [Run-Length Encoding (RLE)](Run-Length%20Encoding/). Store repeated values as a single byte and a count.
- [Huffman Coding](Huffman%20Coding/). Store more common elements using a smaller number of bits.

### 기타

- [Shuffle](Shuffle/). Randomly rearranges the contents of an array.
- [Comb Sort](Comb%20Sort/). An improve upon the Bubble Sort algorithm.
- [Convex Hull](Convex%20Hull/).
- [Miller-Rabin Primality Test](Miller-Rabin%20Primality%20Test/). Is the number a prime number?
- [MinimumCoinChange](MinimumCoinChange/). A showcase for dynamic programming.
- [Genetic](Genetic/). A simple example on how to slowly mutate a value to its ideal form, in the context of biological evolution.
- [Myers Difference Algorithm](Myers%20Difference%20Algorithm/). Finding the longest common subsequence of two sequences.

### 수학

- [Greatest Common Divisor (GCD)](GCD/). Special bonus: the least common multiple.
- [Permutations and Combinations](Combinatorics/). Get your combinatorics on!
- [Shunting Yard Algorithm](Shunting%20Yard/). Convert infix expressions to postfix.
- [Karatsuba Multiplication](Karatsuba%20Multiplication/). Another take on elementary multiplication.
- [Haversine Distance](HaversineDistance/). Calculating the distance between 2 points from a sphere.
- [Strassen's Multiplication Matrix](Strassen%20Matrix%20Multiplication/). Efficient way to handle matrix multiplication.

### 머신 러닝

- [k-Means Clustering](K-Means/). Unsupervised classifier that partitions data into *k* clusters.
- k-Nearest Neighbors
- [Linear Regression](Linear%20Regression/). A technique for creating a model of the relationship between two (or more) variable quantities.
- Logistic Regression
- Neural Networks
- PageRank
- [Naive Bayes Classifier](Naive%20Bayes%20Classifier/)
- [Simulated annealing](Simulated%20annealing/). Probabilistic technique for approximating the global maxima in a (often discrete) large search space.

## 자료 구조
특정 업무에 맞는 상황에 따른 자료구조 선택하기

먼저, 당신의 데이터의 형태와 코드 동작의 종류가 있을 것입니다. 만약 당신이 키(key)를 통해 객체를 찾고 싶다면 딕셔너리(dictionary)가 알맞을 것입니다. 계층적인 데이터를 가지고 있다면 정렬된 트리 구조를 찾아야 할 것입니다. 혹은 당신의 데이터가 순차적이라면 스택(stack) 또는 큐(queue)가 알맞습니다.

두번째,  명확한 자료구조를 선택하여 동작하도록 하는 것이 중요합니다.
예를 들어, 컬렉션에서 가장 중요한 객체를 찾아야한다면, 힙(heap) 또는 우선순위 큐(priority queue)가 일반적인 배열보다 적절할 것입니다.

### 배열 변형

- [Array2D](Array2D/). A two-dimensional array with fixed dimensions. Useful for board games.
- [Bit Set](Bit%20Set/). A fixed-size sequence of *n* bits.
- [Fixed Size Array](Fixed%20Size%20Array/). When you know beforehand how large your data will be, it might be more efficient to use an old-fashioned array with a fixed size.
- [Ordered Array](Ordered%20Array/). An array that is always sorted.
- [Rootish Array Stack](Rootish%20Array%20Stack/). A space and time efficient variation on Swift arrays.

### 큐

- [Stack](Stack/). Last-in, first-out!
- [Queue](Queue/). First-in, first-out!
- [Deque](Deque/). A double-ended queue.
- [Priority Queue](Priority%20Queue). A queue where the most important element is always at the front.
- [Ring Buffer](Ring%20Buffer/). Also known as a circular buffer. An array of a certain size that conceptually wraps around back to the beginning.

### 리스트

- [Linked List](Linked%20List/). A sequence of data items connected through links. Covers both singly and doubly linked lists.
- [Skip-List](Skip-List/). Skip List is a probabilistic data-structure with same logarithmic time bound and efficiency as AVL/ or Red-Black tree and provides a clever compromise to efficiently support search and update operations.

### 트리

- [Tree](Tree/). A general-purpose tree structure.
- [Binary Tree](Binary%20Tree/). A tree where each node has at most two children.
- [Binary Search Tree (BST)](Binary%20Search%20Tree/). A binary tree that orders its nodes in a way that allows for fast queries.
- [Red-Black Tree](Red-Black%20Tree/). A self balancing binary search tree.
- [Splay Tree](Splay%20Tree/). A self balancing binary search tree that enables fast retrieval of recently updated elements.
- [Threaded Binary Tree](Threaded%20Binary%20Tree/). A binary tree that maintains a few extra variables for cheap and fast in-order traversals.
- [Segment Tree](Segment%20Tree/). Can quickly compute a function over a portion of an array.
  - [Lazy Propagation](https://github.com/raywenderlich/swift-algorithm-club/tree/master/Segment%20Tree/LazyPropagation)
- kd-Tree
- [Sparse Table](Sparse%20Table/). Another take on quickly computing a function over a portion of an array, but this time we'll make it even quicker!.
- [Heap](Heap/). A binary tree stored in an array, so it doesn't use pointers. Makes a great priority queue.
- Fibonacci Heap
- [Trie](Trie/). A special type of tree used to store associative data structures.
- [B-Tree](B-Tree/). A self-balancing search tree, in which nodes can have more than two children.
- [QuadTree](QuadTree/). A tree with 4 children.
- [Octree](Octree/). A tree with 8 children.

### 해싱

- [Hash Table](Hash%20Table/). Allows you to store and retrieve objects by a key. This is how the dictionary type is usually implemented.
- Hash Functions

### 셋

- [Bloom Filter](Bloom%20Filter/). A constant-memory data structure that probabilistically tests whether an element is in a set.
- [Hash Set](Hash%20Set/). A set implemented using a hash table.
- [Multiset](Multiset/). A set where the number of times an element is added matters. (Also known as a bag.)
- [Ordered Set](Ordered%20Set/). A set where the order of items matters.

### 그래프

- [Graph](Graph/)
- [Breadth-First Search (BFS)](Breadth-First%20Search/)
- [Depth-First Search (DFS)](Depth-First%20Search/)
- [Shortest Path](Shortest%20Path%20%28Unweighted%29/) on an unweighted tree
- [Single-Source Shortest Paths](Single-Source%20Shortest%20Paths%20(Weighted)/)
- [Minimum Spanning Tree](Minimum%20Spanning%20Tree%20%28Unweighted%29/) on an unweighted tree
- [Minimum Spanning Tree](Minimum%20Spanning%20Tree/)
- [All-Pairs Shortest Paths](All-Pairs%20Shortest%20Paths/)
- [Dijkstra's shortest path algorithm](Dijkstra%20Algorithm/)

## Puzzles

A lot of software developer interview questions consist of algorithmic puzzles. Here is a small selection of fun ones. For more puzzles (with answers), see [here](http://elementsofprogramminginterviews.com/) and [here](http://www.crackingthecodinginterview.com).

- [Two-Sum Problem](Two-Sum%20Problem/)
- [Three-Sum/Four-Sum Problem](3Sum%20and%204Sum/)
- [Fizz Buzz](Fizz%20Buzz/)
- [Monty Hall Problem](Monty%20Hall%20Problem/)
- [Finding Palindromes](Palindromes/)
- [Dining Philosophers](DiningPhilosophers/)
- [Egg Drop Problem](Egg%20Drop%20Problem/)
- [Encoding and Decoding Binary Tree](Encode%20and%20Decode%20Tree/)
- [Closest Pair](Closest%20Pair/)


## 저작권

The Swift Algorithm Club was originally created by [Matthijs Hollemans](https://github.com/hollance).

It is now maintained by [Vincent Ngo](https://www.raywenderlich.com/u/jomoka), [Kelvin Lau](https://github.com/kelvinlauKL), and [Richard Ash](https://github.com/richard-ash).

The Swift Algorithm Club is a collaborative effort from the [most algorithmic members](https://github.com/raywenderlich/swift-algorithm-club/graphs/contributors) of the [raywenderlich.com](https://www.raywenderlich.com) community. We're always looking for help - why not [join the club](.github/CONTRIBUTING.md)? :]

## 라이센스

All content is licensed under the terms of the MIT open source license.

By posting here, or by submitting any pull request through this forum, you agree that all content you submit or create, both code and text, is subject to this license.  Razeware, LLC, and others will have all the rights described in the license regarding this content.  The precise terms of this license may be found [here](https://github.com/raywenderlich/swift-algorithm-club/blob/master/LICENSE.txt).

[![Build Status](https://travis-ci.org/raywenderlich/swift-algorithm-club.svg?branch=master)](https://travis-ci.org/raywenderlich/swift-algorithm-club)

## 번역
<a href="mailto:pierrotcw@naver.com">cwJohnPark</a>
