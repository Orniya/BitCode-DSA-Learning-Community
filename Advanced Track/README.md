# BitCode DSA Roadmap — Advanced Track 🏆

## 🔍 Overview

This roadmap is for the **Advanced cohort** — applicants placed here stay on this track for the **full bootcamp** (parallel to Beginner and Intermediate). You should already be strong on NeetCode 150–style patterns, trees, graphs, introductory DP, and **medium** problems under mild time pressure.

It blends **interview hardening** with **competitive / advanced algorithm** topics seen in curricula such as [DSA_102 Phase D–F](https://github.com/dip4k/DSA_102), [ACM-ICPC preparation guides](https://github.com/BedirT/ACM-ICPC-Preparation), and advanced industry syllabi ([Kunal Kushwaha — advanced section](https://github.com/kunal-kushwaha/DSA-Bootcamp-Java/blob/main/SYLLABUS.md)).

Outcomes:

- Solve **hard** LeetCode-style problems in core families
- Handle **advanced DP, graphs, strings, and greedy** proofs
- Know when **segment trees, tries, union-find, and bit tricks** apply
- Optional path into **competitive programming** with C++

**Bootcamp rhythm:** Weekly **Codeforces mashup** (advanced division) + **two mock sessions** on [Exponent Practice](https://www.tryexponent.com/practice) with your advanced cohort. See [Bootcamp Events](../Bootcamp%20Events/README.md).

**Problem lists:** Weekly hard sets → [problems/](problems/README.md) (add LeetCode links in each file).

---

## 🐍 Language guidance

| Profile | Recommendation |
| --- | --- |
| Interview-focused, strong Python in daily practice | **Python** is enough for most hard interview problems |
| Competitive programming, ICPC, or heavy STL use | **C++** is the usual choice — fast I/O, rich STL, contest ecosystem |
| Already fluent in C++ on placement | **Stay on C++** for this track |

**Why C++ appears here more often:** contest environments and resources ([CP-Algorithms](https://cp-algorithms.com/), *Competitive Programmer’s Handbook*) assume C++-style STL. That is a **valid reason** to switch or stay in C++ for Advanced — not a requirement for software engineering interviews.

**If you are still shaky on mediums in Python,** do not switch languages yet; depth beats syntax churn.

---

## 📋 Expected at registration (placement)

- NeetCode 150 core categories mostly comfortable at **medium** level
- Trees, graphs (BFS/DFS), backtracking, 1D/2D DP fundamentals
- Can run a timed mock and explain trade-offs aloud
- Personal error log (wrong transitions, off-by-one, missing base cases)

---

## 💡 Phases

### Phase 1 — Hard interview consolidation (weeks 1–2)

| Focus | Topics |
| --- | --- |
| **DP depth** | State compression intro, knapsack variants, interleaving strings, DP on trees intro |
| **Graph depth** | Dijkstra, Bellman-Ford (awareness), MST (Prim/Kruskal), multi-source BFS |
| **Binary search mastery** | Binary search on answer, ternary search (select problems) |
| **Monotonic structures** | Monotonic queue/stack for histogram / sliding max |

**Practice:** LeetCode / NeetCode **hard** filter by tag; revisit top 20 missed mediums until automatic.

**Target:** 3–4 timed problems per week with post-mortem notes.

---

### Phase 2 — Greedy & advanced paradigms (week 2–3)

| Topic | Notes |
| --- | --- |
| **Greedy proofs** | Exchange argument intuition, interval scheduling, Huffman (conceptual) |
| **Divide & conquer** | Merge sort thinking, inversion count, closest pair (awareness) |
| **Amortized analysis** | Union-find with path compression, disjoint set rank |

Aligns with [DSA_102 Phase D — Algorithm Paradigms](https://github.com/dip4k/DSA_102).

---

### Phase 3 — Advanced data structures (weeks 3–5)

| Structure | Typical use |
| --- | --- |
| **Trie** | Prefix search, autocomplete-style problems |
| **Union-Find (DSU)** | Dynamic connectivity, Kruskal-style tasks |
| **Segment tree** | Range queries with updates |
| **Fenwick tree (BIT)** | Prefix/range frequency when segtree is overkill |
| **Sparse table** | Static range min/max queries |
| **Heap variants** | Two-heap median, lazy deletion |

Reference: [ACM-ICPC preparation — advanced trees](https://github.com/BedirT/ACM-ICPC-Preparation), [advanced DSA overview](https://pwskills.com/blog/dsa/advance-data-structure-and-algorithms).

**Practice:** Mix **LC hard / CF Div 2 B–C** (if doing contests) with implementation drills — build DS once by hand, then use library templates.

**🎤 Mock #1:** After this phase, one **Exponent** DSA session (~1 hr, peer roles). Details: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

### Phase 4 — String algorithms (week 5–6)

| Topic | Level |
| --- | --- |
| **Rolling hash** | Substring compare, collision awareness |
| **KMP / Z-algorithm** | Pattern matching |
| **Suffix structures** | Awareness: suffix array / automaton (deep dive optional) |

From [Kunal Kushwaha syllabus — strings / Karp-Rabin](https://github.com/kunal-kushwaha/DSA-Bootcamp-Java/blob/main/SYLLABUS.md).

---

### Phase 5 — Bit manipulation & math for contests (week 6–7)

| Topic | Use |
| --- | --- |
| **Bitmask DP** | Subset enumeration, assignment problems |
| **XOR tricks** | Prefix XOR, missing/repeating numbers |
| **Modular arithmetic** | Fast pow, combinatorics with mod (intro) |
| **Number theory (optional)** | GCD, sieve, prime factorization — CP track only |

---

### Phase 6 — “Design” and integration (week 7–8)

| Topic | Examples |
| --- | --- |
| **Design data structure** | LRU cache, LFU intro, rate limiter sketch |
| **System-flavored DS** | Twitter feed / search suggestions (LeetCode design family) |
| **Mixed review sets** | Random hard pulls across DP + graph + heap |

[DSA Handbook Part 13 — Design the Data Structure](https://dsa.handbook.academy/).

**🎤 Mock #2:** Second **Exponent** DSA session — schedule after this phase (medium/hard, trade-off discussion). Details: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

### Phase 7 — Weak areas & optional CP depth

- **Weak-tag sprints:** 5 problems from your worst tag in your error log
- **Optional CP study** (not required for interviews): [CP-Algorithms](https://cp-algorithms.com/), [*Competitive Programmer’s Handbook*](https://cses.fi/book/book.pdf), [USACO Guide](https://usaco.guide/)

---

## 🏁 Weekly contest (advanced division)

Same **contest day** as the rest of the bootcamp; your set is the **advanced division** of the weekly Codeforces mashup (topics aligned with that week’s advanced curriculum).

Schedule: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

## 📂 Suggested topic order (advanced)

```text
Hard mediums review → Advanced DP & graphs → Greedy / amortized
    → Trie / DSU / segtree / BIT → Strings → Bits / math (CP)
        → Design problems → Exponent mocks + weekly mashups
```

---

## 🎯 End-state competencies

You should be able to:

- Pick graph algorithm (BFS, Dijkstra, topo, DSU) with justification
- Design DP state/transition for non-template hards
- Implement or sketch trie / segtree / BIT for stated constraints
- Finish a **hard** in ~40–45 min with partial credit communication
- (CP path) Solve Div 2 B consistently and C occasionally

---

## 📂 Resources

| Resource | Role |
| --- | --- |
| [NeetCode Pro / hard lists](https://neetcode.io/practice) | Pattern maintenance |
| [LeetCode](https://leetcode.com/) | Hard + company-tagged sets |
| [Bootcamp Events](../Bootcamp%20Events/README.md) | Weekly mashup schedule |
| [Codeforces](https://codeforces.com/) | Upsolve / extra practice |
| [CSES Problem Set](https://cses.fi/problemset/) | Structured advanced drills |
| [CP-Algorithms](https://cp-algorithms.com/) | Reference implementations |
| [DSA_102 complete syllabus](https://github.com/dip4k/DSA_102/blob/main/COMPLETE_SYLLABUS_v13.md) | Phase D–F deep dives |

---

> *At this level you are not collecting solutions — you are training judgment under constraints. 🚀*

**Cohort events:** [Bootcamp Events](../Bootcamp%20Events/README.md)
