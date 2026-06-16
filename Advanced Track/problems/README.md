# BitCode DSA — Advanced Track Problem List 🏆

**11 Weeks · 6–8 Problems Per Week · Medium First, Hard Later**

> On GitHub: A normal click leaves this repo. To open LeetCode in a new tab, use Ctrl+click (Windows/Linux) or ⌘+click (Mac) on the problem name or ↗.

---

## Week 1 — Dynamic Programming: Depth 🧠

> 💡 Write what `dp[i]` or `dp[i][j]` represents in plain English before writing any code. Problems 1–5 are mediums to reactivate DP instincts. Attempt 6–8 only after you've written the state definition for the earlier problems.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Target Sum | Medium | Subset sum with +/- sign assignment — leads into knapsack thinking | 0/1 Knapsack | ↗ |
| 2 | Coin Change II | Medium | Unbounded knapsack — count ways, not min coins | Unbounded Knapsack | ↗ |
| 3 | Ones and Zeroes | Medium | 2D knapsack on character counts | 2D Knapsack | ↗ |
| 4 | Interleaving String | Medium | Two-string DP — `dp[i][j]` = can we form `s3[:i+j]` | 2D DP | ↗ |
| 5 | Last Stone Weight II | Medium | Balance partition — minimize absolute difference | 0/1 Knapsack | ↗ |
| 6 | Edit Distance | Hard | Classic 2D string DP — know all 3 transitions cold | 2D DP | ↗ |
| 7 | Regular Expression Matching | Hard | Pattern DP — match `.` and `*` cases separately | Pattern DP | ↗ |
| 8 | Burst Balloons | Hard | Interval DP — think about which balloon you pop *last* | Interval DP | ↗ |

---

## Week 2 — Greedy: From Intuition to Proof ⚡

> 💡 Before coding, write out why the greedy choice can't be beaten by any reordering. Problem 1 is an easy warm-up — don't skip it.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Maximum Units on a Truck | Easy | Sort by unit value — clean greedy warm-up | Sort + Greedy | ↗ |
| 2 | Non-overlapping Intervals | Medium | Sort by end time, keep non-overlapping | Interval Greedy | ↗ |
| 3 | Partition Labels | Medium | Track last occurrence of each character | Last Occurrence | ↗ |
| 4 | Jump Game II | Medium | Maintain max reachable range per jump | Range Greedy | ↗ |
| 5 | Minimum Number of Arrows to Burst Balloons | Medium | Sort by end, merge overlapping intervals | Interval Greedy | ↗ |
| 6 | Gas Station | Medium | Reset start when cumulative tank goes negative | Circuit Greedy | ↗ |
| 7 | Candy | Hard | Two-pass ratings — left-to-right then right-to-left | Two-Pass Greedy | ↗ |
| 8 | IPO | Hard | Two heaps — available projects + capital threshold | Heap + Greedy | ↗ |

---

## Week 3 — Monotonic Stack & Queue 📚

> 💡 Invariant before coding: *"my stack is always increasing (or decreasing) from bottom to top."* When you push a new element, pop everything that violates the order — those elements just found their answer.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Daily Temperatures | Medium | Next warmer day — the entry problem for mono stack | Mono Stack | ↗ |
| 2 | Online Stock Span | Medium | Backward-looking mono stack | Mono Stack | ↗ |
| 3 | Remove K Digits | Medium | Pop larger digits when a smaller one arrives | Mono Stack | ↗ |
| 4 | 132 Pattern | Medium | Maintain third-element candidate in stack | Mono Stack | ↗ |
| 5 | Sum of Subarray Minimums | Medium | Contribution counting with left/right boundaries | Mono Stack | ↗ |
| 6 | Largest Rectangle in Histogram | Hard | Stack stores indices of increasing heights | Mono Stack | ↗ |
| 7 | Trapping Rain Water | Hard | Stack or two-pointer — compare with histogram approach | Mono Stack | ↗ |
| 8 | Sliding Window Maximum | Hard | Mono deque — front is always the max in current window | Mono Deque | ↗ |

---

## Week 4 — Advanced Graphs: Weighted & Directed 🗺️

> 💡 Implement Dijkstra once from scratch — heap + dist array. After that, use your template freely.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Accounts Merge | Medium | DSU warm-up — group emails by shared account | Union-Find | ↗ |
| 2 | Find Eventual Safe States | Medium | Reverse edges + topo sort (or DFS coloring) | Topo Sort | ↗ |
| 3 | Network Delay Time | Medium | Dijkstra — implement single-source shortest path | Dijkstra | ↗ |
| 4 | Cheapest Flights Within K Stops | Medium | Bellman-Ford with K iterations constraint | Bellman-Ford | ↗ |
| 5 | Min Cost to Connect All Points | Medium | MST — Prim with heap or Kruskal with DSU | MST | ↗ |
| 6 | Swim in Rising Water | Hard | Dijkstra on grid — minimize max edge weight on path | Dijkstra Grid | ↗ |
| 7 | Word Ladder | Hard | BFS shortest path — each word is a node | BFS Shortest | ↗ |
| 8 | Alien Dictionary | Hard | Build graph from adjacent word pairs → topo sort | Topo Sort | ↗ |

---

## Week 5 — Backtracking: Pruning & Constraint Handling 🌿

> 💡 Draw the decision tree for each problem before coding. Identify where you can prune. Do not start coding until you can see the tree.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Restore IP Addresses | Medium | 4 segments, each 0–255, max 3 digits each | Bounded Backtrack | ↗ |
| 2 | Splitting Into Descending Consecutive Values | Medium | Each part must be exactly 1 less than the previous | Constrained Backtrack | ↗ |
| 3 | Palindrome Partitioning II | Hard | DP + backtrack — precompute palindrome ranges | DP + Backtrack | ↗ |
| 4 | Word Break II | Hard | Backtrack + memo — cache results at each index | Backtrack + Memo | ↗ |
| 5 | N-Queens | Hard | Track row, col, and diagonal sets for O(1) pruning | Constraint Backtrack | ↗ |
| 6 | Sudoku Solver | Hard | Fill empty cells, propagate row/col/box constraints | Constraint Backtrack | ↗ |
| 7 | Expression Add Operators | Hard | Track running value AND last operand (needed for `*` undo) | Expression Backtrack | ↗ |

---

## Week 6 — Trie & Prefix Structures 🌲

> 💡 Problem 1 is mandatory — build the trie from scratch with no shortcuts. Every other problem this week uses the same structure you build there.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Implement Trie (Prefix Tree) | Medium | Build children as dict or array[26] — do it by hand | Trie Build | ↗ |
| 2 | Replace Words | Medium | Insert roots, find shortest matching prefix per word | Trie Lookup | ↗ |
| 3 | Map Sum Pairs | Medium | Store values in nodes, sum on prefix traversal | Trie + Sum | ↗ |
| 4 | Maximum XOR of Two Numbers in an Array | Medium | Binary trie (bits 31→0), greedy opposite bit per level | Binary Trie | ↗ |
| 5 | Design Add and Search Words Data Structure | Medium | Wildcard `.` triggers recursive DFS at that node | Trie + DFS | ↗ |
| 6 | Word Search II | Hard | Trie prunes dead branches early in board DFS | Trie + DFS | ↗ |
| 7 | Concatenated Words | Hard | Trie + word break — check if word is built from shorter words | Trie + DP | ↗ |

---

## Week 7 — Grid DP: Focused Set 📐

> ℹ️ Cherry Pickup and Cherry Pickup II are removed — 3D state multi-agent DP is a competitive programming problem, not an interview pattern. This set covers grid DP ideas that do appear in interviews.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Minimum Path Sum | Medium | `dp[i][j]` = min cost to reach cell from top-left | Grid DP | ↗ |
| 2 | Maximal Square | Medium | `dp[i][j]` = side length of largest all-1s square ending here | Grid DP | ↗ |
| 3 | Count Square Submatrices with All Ones | Medium | Same recurrence as Maximal Square — sum instead of max | Grid DP | ↗ |
| 4 | Out of Boundary Paths | Medium | Count paths that exit the grid — track mod carefully | Grid DP + Mod | ↗ |
| 5 | Minimum Falling Path Sum | Medium | Row-by-row DP, min of 3 neighbors from row above | Grid DP | ↗ |
| 6 | Dungeon Game | Hard | Reverse DP from bottom-right — min health needed to survive | Reverse Grid DP | ↗ |
| 7 | Maximal Rectangle | Hard | Extend histogram hard from Week 3 — rebuild per row | Grid + Mono Stack | ↗ |

---

## Week 8 — Design Data Structures 🏗️

> ℹ️ String algorithms (KMP, Z-algorithm, rolling hash) are not in this track. See CP resources in the roadmap if you want them after the bootcamp.

> 💡 For each problem: write the operations and their required time complexity *before* picking data structures.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Design Browser History | Medium | Two stacks or array with pointer — simple warm-up | Stack | ↗ |
| 2 | Time Based Key-Value Store | Medium | HashMap → sorted list of (time, val) → binary search | Hash + BSearch | ↗ |
| 3 | Insert Delete GetRandom O(1) | Medium | Array + HashMap — swap with last on delete | Array + Hash | ↗ |
| 4 | Design Underground System | Medium | Two HashMaps — check-in times + cumulative trip totals | HashMap Composition | ↗ |
| 5 | LRU Cache | Medium | HashMap + doubly linked list — know this cold | Hash + DLL | ↗ |
| 6 | LFU Cache | Hard | Min-freq tracker + freq buckets + DLL per bucket | Freq Buckets | ↗ |
| 7 | All O'one Data Structure | Hard | O(1) inc/dec/getMax/getMin — doubly linked list of buckets | Bucket DLL | ↗ |

---

## Week 9 — Union-Find: Deep Dive 🔗

> ℹ️ Segment Trees and BITs are not in this track — competitive programming structures. Range Sum Query (Mutable) is included as a single awareness-level problem only.

> 💡 Implement DSU with path compression and union by rank from scratch. After this week it should take under 10 minutes cold.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Redundant Connection | Medium | Add edges — first edge that creates a cycle is the answer | DSU Cycle | ↗ |
| 2 | Number of Connected Components in an Undirected Graph | Medium | Union all edges, count remaining distinct roots | DSU Count | ↗ |
| 3 | Graph Valid Tree | Medium | n-1 edges AND no cycle — check both | DSU + Edges | ↗ |
| 4 | Most Stones Removed with Same Row or Column | Medium | Union stones sharing a row or column | DSU Coordinates | ↗ |
| 5 | Satisfiability of Equality Equations | Medium | Union equalities first, then verify inequalities | DSU Grouping | ↗ |
| 6 | Redundant Connection II | Hard | Directed graph — two candidate edges, check which breaks the tree | Directed DSU | ↗ |
| 7 | Range Sum Query - Mutable | Medium | BIT/Fenwick tree — see the pattern once, high level is enough | BIT Awareness | ↗ |

---

## Week 10 — Bit Manipulation: Interview Essentials 🔧

> ℹ️ Bitmask DP (TSP, assignment problems) is removed — competitive programming territory. This week covers XOR tricks and bitmask enumeration, which actually appear in interviews.

| # | Problem | Difficulty | Notes | Pattern Tag | ↗ |
|---|---------|------------|-------|-------------|---|
| 1 | Number of 1 Bits | Easy | `n & (n-1)` clears the lowest set bit — count iterations | Bit Trick | ↗ |
| 2 | Counting Bits | Easy | `dp[i] = dp[i >> 1] + (i & 1)` | Bit DP | ↗ |
| 3 | Single Number | Easy | XOR all — pairs cancel, lone number survives | XOR | ↗ |
| 4 | Single Number II | Medium | Bit count mod 3 — generalizes to any k | Bit Count | ↗ |
| 5 | Single Number III | Medium | XOR split — separate the two unique numbers | XOR Split | ↗ |
| 6 | Sum of Two Integers | Medium | `carry = (a & b) << 1`, `sum = a ^ b`, repeat | Bit Add | ↗ |
| 7 | Maximum XOR of Two Numbers in an Array | Medium | Binary trie — greedy opposite bit (revisit from Week 6) | Binary Trie | ↗ |
| 8 | Subsets | Medium | Iterate `0` to `2^n`, check each bit for inclusion | Bitmask Enum | ↗ |

---

## Week 11 — Mock Week: Timed Practice & Review 🎯

> No new problems this week. Pick your 2 weakest weeks, re-solve without hints, then do the second Exponent mock.

| # | Activity | Time | Notes |
|---|----------|------|-------|
| 1 | Identify your 2 weakest topic weeks | 30 min | Which problems needed hints or the editorial? |
| 2 | Re-solve 3–4 problems from each weak week | 2–3 hrs | No hints — if stuck after 25 min, note why and move on |
| 3 | Timed mediums (your choice) | 2 hrs | 25 min per problem — verbalize approach before coding |
| 4 | Timed hards (your choice) | 2 hrs | 35–40 min — partial credit counts, keep communicating |
| 5 | Exponent Mock #2 | 1 hr | Full peer mock with advanced cohort |
| 6 | Post-mock review | 45 min | Write down every pattern you misidentified or missed |

---

> *Every hard problem you struggle with today is a medium you'll solve in 10 minutes next month. ☘️*
