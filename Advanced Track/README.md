# BitCode DSA Roadmap — Advanced Track 🏆

## 🔍 Overview

This track is for students who completed or are comfortable with the **Intermediate roadmap**. You know the core NeetCode 150 patterns — arrays, two pointers, trees, basic graphs, and introductory DP. This track builds on that directly: harder mediums first, then selected hards once patterns are solid.

The goal is **not** to cover every advanced algorithm. It is to deepen what you already know and add the patterns most likely to appear in real interviews.

> ⚠️ **This is not a competitive programming track.** KMP, suffix arrays, segment trees, bitmask DP, and contest-style algorithms are not covered here. This track stays interview-focused throughout.

**Bootcamp rhythm:** Weekly **Codeforces mashup** (advanced division) + **two mock sessions** on [Exponent Practice](https://www.tryexponent.com/practice) with your advanced cohort. See [Bootcamp Events](../Bootcamp%20Events/README.md).

**Problem list:** → [problems/README.md](problems/README.md)

---

## 🐍 Language guidance

| Profile | Recommendation |
| --- | --- |
| Strong Python in daily practice | **Stay on Python** — it's enough for everything in this track |
| Already writing DSA in C++ | **Continue in C++** — STL habits carry over cleanly |
| Switching languages AND learning new patterns | **Don't switch** — depth beats syntax churn |

---

## 📋 Expected at registration

- NeetCode 150 core categories mostly comfortable at **medium** level
- Trees, graphs (BFS/DFS), backtracking, 1D/2D DP fundamentals
- Can run a timed mock and explain trade-offs aloud
- Personal error log (wrong transitions, off-by-one, missing base cases)

---

## 💡 Phases

Each phase ramps in difficulty: **problems 1–5 are mediums** to build confidence and pattern recognition, **problems 6–7 are harder mediums or accessible hards**. This is intentional — do not skip the mediums.

---

### Phase 1 — DP Depth (weeks 1–2) 🧠

You have seen 1D and basic 2D DP. This phase goes deeper: knapsack variants, two-string DP, and interval DP. Start with the mediums to reactivate DP instincts before touching the hards.

> 💡 Before coding anything, write what `dp[i]` or `dp[i][j]` represents in plain English.

| Topic | Concepts |
| --- | --- |
| **Knapsack variants** | 0/1, unbounded, 2D knapsack |
| **Two-string DP** | Interleaving, edit distance |
| **Interval DP** | Think about what you pick *last*, not first |

**Practice:** NeetCode 150 — **1-D DP** and **2-D DP** (medium problems first).

---

### Phase 2 — Greedy & Monotonic Structures (week 2–3) ⚡

Greedy is often misunderstood as "pick the best option each step." The real skill is knowing *why* that works. Monotonic stack/deque is covered here because both patterns share the same underlying logic: local decisions that provably don't hurt the global answer.

> 💡 For greedy: write out why the greedy choice can't be beaten by any reordering before coding. For monotonic stack: write the invariant first — *"my stack is always increasing from bottom to top."*

| Topic | Concepts |
| --- | --- |
| **Interval scheduling** | Sort by end time, overlap removal |
| **Range greedy** | Jump game, max reachable range |
| **Heap + greedy** | Two-phase problems (capital + profit) |
| **Monotonic stack** | Next greater/smaller, contribution counting, histogram |
| **Monotonic deque** | Sliding window max/min |

**Practice:** NeetCode 150 — **Greedy**, **Intervals**, **Stack** (hard problems).

---

### Phase 3 — Advanced Graphs (weeks 3–4) 🗺️

You know BFS and DFS. This phase adds shortest paths (Dijkstra), directed graph ordering (topological sort), and Union-Find for connectivity — the three graph tools that cover almost everything in interviews beyond basic traversal.

> 💡 Implement Dijkstra once from scratch — heap + dist array. After that you can use the template freely.

| Topic | Concepts |
| --- | --- |
| **Dijkstra** | Single-source shortest path, grid variants |
| **Bellman-Ford** | K-constrained shortest path |
| **MST** | Prim or Kruskal — pick one and know it |
| **Topological sort** | Kahn's or DFS post-order |
| **Union-Find** | Connectivity, cycle detection |

**Practice:** NeetCode 150 — **Graphs** and **Advanced Graphs**.

---

### Phase 4 — Backtracking & Trie (weeks 4–5) 🌿🌲

Two patterns that are often under-practiced at this level. Backtracking here means harder constraint problems where pruning is the bottleneck, not the recursion itself. Tries are simpler to implement than they look — build one from scratch and the rest of the week's problems follow naturally.

> 💡 Backtracking: draw the decision tree first, identify where to prune, then code. Trie: Problem 1 is mandatory from scratch — every other problem reuses that structure.

| Topic | Concepts |
| --- | --- |
| **Bounded branching** | IP addresses, number partitions |
| **Backtrack + memo** | Cache results at each index to avoid recomputation |
| **Constraint propagation** | Sudoku-style pruning |
| **Standard trie** | Prefix search, word validation, autocomplete |
| **Binary trie** | XOR maximization |
| **Trie + DFS** | Wildcard matching, board search |

**Practice:** NeetCode 150 — **Backtracking** (hard problems), **Tries**.

---

### Phase 5 — Grid DP & Design Data Structures (weeks 5–7) 📐🏗️

Two distinct topics covered together because they're both consolidation-heavy — they build on patterns from earlier phases rather than introducing fundamentally new thinking.

Grid DP: define your state as position(s) on the grid, build up from base cases, identify what transitions are valid.

Design: the skill is identifying which structure handles each operation, then composing them to hit multiple O(1) constraints.

> ℹ️ **Cherry Pickup II removed** — 3D state multi-agent DP is competitive programming, not an interview pattern. String algorithms (KMP, Z-algo, rolling hash) are also not in this track — see CP resources below if you want them after the bootcamp.

| Topic | Concepts |
| --- | --- |
| **Standard grid DP** | Min path, square detection, path counting |
| **Reverse grid DP** | Solve from destination when forward is ambiguous |
| **Cache design** | LRU (hash + DLL), LFU (frequency buckets) |
| **Time-based structures** | Binary search on timestamps |
| **O(1) insert/delete/random** | Array + hash with swap-on-delete |

**Practice:** NeetCode 150 — **2-D DP** (grid problems), **Design**.

**🎤 Mock #1:** After this phase, complete one **Exponent** DSA session (~1 hr, peer roles). Details: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

### Phase 6 — Union-Find Deep Dive & Bit Manipulation (weeks 7–9) 🔗🔧

Union-Find appeared in Phase 3 for connectivity and cycle detection. This phase goes deeper: path compression, union by rank, and problems where DSU is the right tool but not immediately obvious.

Bit manipulation covers the XOR tricks and bitmask enumeration that actually appear in interviews — not the TSP-style bitmask DP from competitive programming.

> ℹ️ **Segment Trees and BITs are not in this track.** Range Sum Query (Mutable) is included as one awareness-level problem only. Bitmask DP is also removed — see CP resources below.

| Topic | Concepts |
| --- | --- |
| **DSU fundamentals** | Path compression, union by rank |
| **Cycle detection** | Redundant connection, valid tree |
| **Coordinate DSU** | Group elements by shared row/column |
| **XOR patterns** | Cancellation, prefix XOR, missing numbers |
| **Bit counting** | Kernighan's trick, DP on bits |
| **Bitmask enumeration** | Iterate 0 to 2ⁿ for subset problems |

**Practice:** NeetCode 150 — **Advanced Graphs** (DSU problems), **Bit Manipulation**.

---

### Phase 7 — Timed Practice & Mock (weeks 9–11) 🎯

No new topics. This phase is for consolidation, timed reps, and the second Exponent mock. Pick your weakest 2 phases and revisit problems you couldn't solve without hints.

- **Timed mediums:** 25 min per problem — verbalize approach before writing code
- **Timed hards:** 35–40 min — partial credit counts, keep communicating
- **Re-solve** missed problems after 3–7 days
- Apply feedback from Mock #1

**🎤 Mock #2:** Second **Exponent** DSA session with your advanced cohort. Details: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

## 🏁 Weekly Contest

Same contest day as the rest of the bootcamp — your set is the **advanced division** of the weekly Codeforces mashup. Topics align with the current phase's material. Upsolve within 48 hours.

Schedule: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

## 🎓 End-of-Bootcamp Goals

By the end of the bootcamp you should be able to:

- Implement Dijkstra, topological sort, and Union-Find with justification for when each applies
- Derive a DP recurrence for 1D, 2D, and interval DP problems
- Build a trie from scratch and know when prefix structures apply
- Complete most medium problems in 20–25 minutes with correct complexity analysis
- Communicate your approach clearly in both Exponent mocks before writing a line of code

---

## 📂 Resources

| Resource | Use |
| --- | --- |
| [NeetCode 150](https://neetcode.io/practice) | Primary problem set |
| [NeetCode DSA for Beginners](https://neetcode.io/courses/dsa-for-beginners) | Gap-fill reference |
| [LeetCode](https://leetcode.com/) | Company-tagged sets after Phase 5 |
| [Codeforces](https://codeforces.com/) | Weekly mashup + upsolve |
| [CP-Algorithms](https://cp-algorithms.com/) | Optional: string algorithms and segtree *after* bootcamp |
| [Competitive Programmer's Handbook](https://cses.fi/book/book.pdf) | Optional: CP depth only |

---

> *Every hard problem you struggle with today is a medium you'll solve in 10 minutes next month. ☘️*

**Cohort events:** [Bootcamp Events](../Bootcamp%20Events/README.md)
