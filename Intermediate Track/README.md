# BitCode DSA Roadmap — Intermediate Track 🚀📚

## 🔍 Overview

This roadmap is for the **Intermediate cohort** — you were registered at this level for the **full bootcamp**. You should already be comfortable with Python (or your chosen language), arrays/hash, linked lists, stacks/queues, basic recursion, and Big-O.

Goals for the summer:

- Turn concepts into **pattern recognition** under light time pressure
- Cover **trees, graphs, backtracking, and introductory DP** in a deliberate order
- Build consistency toward **NeetCode 150–level** medium problems
- Prepare for interview-style communication (approach → code → complexity)

By the end, you should recognize common patterns quickly, solve most **medium** problems in core NeetCode categories, and know when to reach for BFS, DFS, or a DP state definition.

**Bootcamp rhythm:** Weekly **Codeforces mashup** (intermediate division) + **two mock sessions** on [Exponent Practice](https://www.tryexponent.com/practice) with your intermediate cohort. See [Bootcamp Events](../Bootcamp%20Events/README.md).

**Problem lists:** Full **NeetCode 150** set → [problems/](problems/README.md) (add LeetCode links in each file).

---

## 🐍 Language guidance

| Profile | Recommendation |
| --- | --- |
| Placed in intermediate cohort or still building fluency | **Stay on Python** — fastest path to pattern mastery |
| Already writing DSA in **C++** daily (e.g. past competitive programming) | **Continue in C++** — `std::vector`, `unordered_map`, `queue`, `stack`, and STL algorithms are fine |
| Know Java well and dislike Python | Java is acceptable; same topic order applies |

**Valid reasons to use C++ in this track (not required):** STL performance habits, preparing specifically for ICPC-style contests, or already solving mediums in C++.

**We still recommend Python** if you are switching languages *and* learning trees/DP at the same time — one less variable while difficulty jumps.

---

## 📋 Prerequisites

Expected at registration (placement):

- Python (or chosen language) fluency
- Arrays, hashing, linked lists, stacks, queues
- Recursion basics and Big-O
- ~20+ easy problems solved with complexity notes

---

## 💡 Phases

### Phase 1 — Pattern foundations (weeks 1–2)

Problem-first refresh on high-yield interview patterns ([DSA Handbook](https://dsa.handbook.academy/) Parts 1–4 style; [6-month DSA plans](https://github.com/iankushsingh/dsa-6-month) Month 1).

| Block | Topics | Focus |
| --- | --- | --- |
| A | **Arrays & hashing** | Frequency maps, anagrams, prefix sums (intro) |
| B | **Two pointers** | Opposite ends, same direction, sorted arrays |
| C | **Sliding window** | Fixed/variable window, substring problems |
| D | **Stack** | Monotonic stack intro, valid parentheses, daily temperatures |
| E | **Binary search** | Classic BS, lower/upper bound, search on answer (intro) |
| F | **Linked list** | Reverse, cycle, merge lists |

**Practice:** NeetCode 150 sections — Arrays & Hashing → Two Pointers → Sliding Window → Stack → Binary Search → Linked List.

🔗 [NeetCode practice](https://neetcode.io/practice)

**Cadence:** 1 problem/day minimum; 2–3 on weekends if energy allows. Prioritize **understanding + complexity write-up** over speed.

---

### Phase 2 — NeetCode beginner course (targeted modules)

Revisit [DSA for Beginners](https://neetcode.io/courses/dsa-for-beginners) modules you skipped in Beginner — especially **trees** and any **graph/DP previews** — with a problem-first mindset.

Use this as **structured theory + exercises** before hard NeetCode 150 tree/graph/DP sets.

---

### Phase 3 — Trees & heaps (weeks 3–4)

Trees are the **checkpoint** topic for everything non-linear ([LeetCopilot phase model](https://leetcopilot.dev/blog/what-order-to-learn-data-structures-algorithms)).

| Topic | Concepts |
| --- | --- |
| **Binary trees** | Traversals (in/pre/post/level), height, diameter |
| **BST** | Search, insert delete concepts, validate BST |
| **Recursion on trees** | Path sum, LCA intro, subtree problems |
| **Heaps / priority queues** | Top-K, merge K lists, scheduling patterns |

**Practice:** NeetCode 150 — **Trees**, then **Heap / Priority Queue**.

---

### Phase 4 — Graphs (weeks 4–5)

| Topic | Concepts |
| --- | --- |
| **Representations** | Adjacency list/matrix, grid as graph |
| **BFS** | Shortest path in unweighted graphs, level order |
| **DFS** | Components, islands, cycle detection (intro) |
| **Topological sort** | Kahn’s algorithm / DFS post-order |
| **Union-Find (intro)** | Connected components, redundant connection |

**Practice:** NeetCode 150 — **Graphs**.

---

### Phase 5 — Backtracking & greedy (week 5–6)

| Topic | Concepts |
| --- | --- |
| **Backtracking** | Subsets, permutations, combinations, constraint pruning |
| **Greedy** | Local choice proofs at medium level, intervals, scheduling |

**Practice:** NeetCode 150 — **Backtracking**, **Greedy** (as listed on NeetCode).

---

### Phase 6 — Dynamic programming I (weeks 6–8)

DP needs recursion + patterns from prior phases ([DSA Master Curriculum](https://github.com/dip4k/DSA_102) Phase C).

| Stage | Patterns |
| --- | --- |
| **1D DP** | Climbing stairs, house robber, coin change (intro) |
| **Sequence DP** | LIS intro, edit distance intro |
| **Grid DP** | Unique paths, min path sum |
| **State machines** | Buy/sell stock variants |

**Practice:** NeetCode 150 — **1-D DP** and **2-D DP** sections; start 1D before 2D.

**🎤 Mock #1:** After this phase, complete one **Data Structures & Algorithms** session on [Exponent](https://www.tryexponent.com/practice) (~1 hr, peer roles). Details: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

### Phase 7 — NeetCode 150 core run (ongoing)

Full pass in recommended order (aligns with [NeetCode 150](https://neetcode.io/practice) and FAANG-style roadmaps):

1. Arrays & Hashing  
2. Two Pointers  
3. Sliding Window  
4. Stack  
5. Binary Search  
6. Linked List  
7. Trees  
8. Tries (optional if time tight)  
9. Heap / Priority Queue  
10. Backtracking  
11. Graphs  
12. Advanced Graphs (if on your list)  
13. 1-D DP  
14. 2-D DP  
15. Greedy  
16. Intervals  
17. Math & geometry (light)  
18. Bit manipulation (intro)

**Targets by end of summer intermediate phase:**

- **~80–120** NeetCode 150 problems attempted (quality > checkbox)
- **~60%+** mediums solved with minimal hints after revisit
- Written **pattern tags** per problem in your own tracker

---

### Phase 8 — Timed practice (final 1–2 weeks)

- **Timed reps:** 25–35 min per medium, talk through approach aloud
- **Re-solve** missed problems after 3–7 days
- Apply feedback from **Exponent mock #1**

**🎤 Mock #2:** During or right after this phase — second **Exponent** DSA session with your intermediate cohort. Details: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

## 🏁 Weekly contest (intermediate division)

On cohort **contest day** each week, the mashup **intermediate division** matches recent topics (e.g. sliding window week → window-style problems). Upsolve within 48 hours.

Schedule and division rules: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

## 📂 Resources

| Resource | Use |
| --- | --- |
| [NeetCode 150](https://neetcode.io/practice) | Primary problem set |
| [DSA for Beginners](https://neetcode.io/courses/dsa-for-beginners) | Gap-fill for trees/graphs/DP |
| [DSA Handbook](https://dsa.handbook.academy/) | Reference reading by part |
| [Kunal Kushwaha DSA syllabus](https://github.com/kunal-kushwaha/DSA-Bootcamp-Java/blob/main/SYLLABUS.md) | Topic checklist (language-agnostic order) |

---

## 🎓 End-of-bootcamp goals (intermediate cohort)

By the end of the summer you should be able to:

- Implement BFS/DFS and explain when each applies
- Derive a DP recurrence for classic 1D/2D mediums
- Complete most **NeetCode 150** categories at medium difficulty with revisits
- Communicate solutions clearly in both Exponent mocks

---

> *Every problem you struggle with is quietly building the version of you that solves it in seconds later. ☘️✨*

**Cohort events:** [Bootcamp Events](../Bootcamp%20Events/README.md)
