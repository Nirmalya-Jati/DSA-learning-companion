# Nodes & Notation — A Data Structure Notebook

An interactive, single-page web app for learning data structures. Every structure gets a live, step-by-step visualization, plain-English theory, complexity analysis, and full working implementations across 14 programming languages — all in one self-contained HTML file.

## Features

- **16 interactive core structures** with animated, step-through operations (play/pause, step forward/back, adjustable speed)
- **Theory & Algorithm** panel for each structure: how it works, why, and when to use it
- **Complexity tables** (Big-O) for every operation
- **Pseudocode** that highlights in sync with the animation
- **Full implementations** in 14 languages, organized by operation
- **60+ topic reference library** covering algorithms and advanced structures beyond the core set, with search
- **Light/dark themes** and responsive **mobile/desktop layouts**

## Core interactive structures

| Structure | Structure | Structure | Structure |
|---|---|---|---|
| Array | Stack | Queue | Linked List |
| Binary Search Tree | Matrix / 2D Array | String | Doubly Linked List |
| Circular Linked List | Deque | Heap (Priority Queue) | Graph |
| Digraph (weighted, Dijkstra) | Hash Table | Trie | Disjoint Set Union |

Each structure includes hands-on operations (e.g. Array: access, search, binary search, insert, delete, update; Graph: add edge, BFS, DFS; Digraph: Dijkstra's shortest path) with a custom "build your own" input so you can test with your own values.

## Reference library

A searchable sidebar of 60+ additional topics, grouped by category:

- **Prerequisites** — Complexity Analysis (Big-O)
- **Sorting algorithms** — Bubble, Selection, Insertion, Merge, Quick, Heap, Counting, Radix, Bucket Sort
- **Linear structures** — Sparse Arrays/Matrices, Skip Lists
- **Tree variants** — AVL, Red-Black, N-ary, B-Trees/B+ Trees, Persistent Segment Trees, Treaps, Splay Trees, Suffix Trees/Arrays
- **Graph-related** — Adjacency List vs Matrix, Weighted Graphs & DAGs, Minimum Spanning Trees, Cycle Detection, Connected Components
- **Hashing extensions** — Bloom Filters, Cuckoo Hashing, Load Factor & Rehashing
- **Specialized / string structures** — Rope, LRU/LFU Cache
- **Traversal & paradigms** — BFS/DFS/pre-in-post-order, Persistent Data Structures, Concurrent Data Structures
- **Interval & range structures** — Interval Trees, K-D Trees, Range Trees, Sqrt Decomposition
- **Specialized trees** — Segment/Fenwick Trees, Ternary Search Trees, Van Emde Boas Trees, Cartesian Trees, Merkle Trees
- **Set / multiset variants** — Ordered Sets/Multisets, Fibonacci Heaps, Binomial Heaps
- **Spatial & geometric structures** — Quad Trees, Octrees, R-Trees
- **Memory-related** — Circular/Ring Buffers, Memory/Object Pools
- **Abstract concepts** — Abstract Data Types, Amortized Analysis
- **Probabilistic & streaming structures** — Count-Min Sketch, HyperLogLog, Skip Graphs
- **String-matching structures** — Suffix Automaton, Z-function, Aho-Corasick Automaton
- **External memory / disk-based** — LSM Trees, External Merge Structures
- **Persistent & functional structures** — Persistent Arrays, Zipper, Finger Trees
- **Specialized graph structures** — Link-Cut Trees, Euler Tour Trees

## Implementation languages

JavaScript, Python, Java, C++, Go, C, C#, Rust, TypeScript, Swift, Kotlin, Ruby, PHP, Scala.

## Getting started

This is a single, dependency-free HTML file.

## Tech notes

- Pure HTML/CSS/JavaScript — no framework
- Visualizations render with a mix of DOM elements and SVG (`svgLayer`) for connectors/edges
- A canvas-based drifting node/edge background animation runs behind the content
- Mobile view auto-fits each visualization's bounding box to the screen width; desktop uses a fixed 900×340 stage
- Theme (light/dark) and device mode (mobile/desktop) are user-toggleable
