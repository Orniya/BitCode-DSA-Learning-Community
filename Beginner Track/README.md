# BitCode DSA Roadmap — Beginner Track 📚

## 🔍 Overview

This roadmap is for the **Beginner cohort** — applicants placed here stay on this track for the **full bootcamp** (parallel to Intermediate and Advanced, not a step before them).

The pace fits a **summer bootcamp**: build habits early, practice daily, and hit the end-of-track goals below.

We focus on:

- Strong **Python** fundamentals (our default language for this track)
- Transitioning from syntax → small problems → structured DSA
- Core linear structures and basic patterns
- Introducing **time and space complexity** before harder topics

By the end, you should comfortably solve **easy** problems on arrays, strings, hashing, linked lists, stacks, and queues, and understand recursion at a basic level. **Trees, graphs, and dynamic programming belong in the Intermediate Track** — they build on everything here and are too heavy for true beginners in one summer phase.

**Bootcamp rhythm:** **Weekly Codeforces mashup** (beginner division only). No formal mock block at this level — see [Bootcamp Events](../Bootcamp%20Events/README.md).

**Problem lists:** [problems/](problems/README.md) — add your LeetCode links in each table.

---

## 🐍 Language: Python (recommended)

**Use Python for this track** unless you already have a strong reason to use something else.

| Situation | Recommendation |
| --- | --- |
| New to programming or still exploring | **Python** — readable syntax, fast feedback, great for learning patterns |
| Already comfortable in another language *and* completing warm-ups easily | You may continue in that language; tell mentors so you can be grouped for reviews |
| Want C++ / Java for interviews later | Finish **Beginner** in Python first, then switch in Intermediate if you prefer |

**Why not push C++ here?** STL and memory details add cognitive load before algorithmic thinking. Python keeps the focus on logic, complexity, and problem decomposition. Competitive-programming-style C++ is optional from the **Intermediate** track onward for students who are already fluent in it.

🔗 [Python basics on HackerRank](https://www.hackerrank.com/domains/python?filters%5Bskills%5D%5B%5D=Python%20%28Basic%29)

---

## 💡 Phases

### 1. Python fundamentals

Start with **Python basics** (HackerRank “Python Basic” or equivalent). Cover only what DSA needs:

- Variables, types, `input` / `print`
- Conditionals and loops
- Functions and simple modules
- Lists, tuples, dictionaries, sets
- List comprehensions and common built-ins (`len`, `sorted`, `enumerate`, `zip`)

Skip deep OOP, web frameworks, and tooling rabbit holes for now.

---

### 2. Warm-up problems

Move from “I can write syntax” to “I can solve a spec.”

🔗 [HackerRank — Warmup](https://www.hackerrank.com/domains/algorithms?filters%5Bsubdomains%5D%5B%5D=warmup&badge_type=problem-solving)

Aim for **10–15** problems. Focus on reading the problem twice, edge cases, and clean I/O — not tricks.

---

### 3. Implementation problems

Practice breaking problems into steps and implementing them end-to-end.

🔗 [HackerRank — Implementation](https://www.hackerrank.com/domains/algorithms?filters%5Bsubdomains%5D%5B%5D=implementation)

---

### 4. Big O and complexity

Learn **why** solutions differ in speed and memory before piling on more structures.

🔗 [NeetCode — Big O notation](https://neetcode.io/courses/lessons/big-o-notation)

**Checkpoint:** Short quiz on common complexities (`O(1)`, `O(log n)`, `O(n)`, `O(n log n)`, `O(n²)`) and when they appear.

---

### 5. DSA for beginners (selected topics only)

Use NeetCode’s **DSA for Beginners** course in a **curated order**. Work roughly **one topic per day** with its exercises.

🔗 [DSA for Beginners](https://neetcode.io/courses/dsa-for-beginners)

#### ✅ In scope for this track

| Topic | Why it’s here |
| --- | --- |
| **Arrays & strings** | Foundation for almost every interview problem |
| **Hash maps / sets** | Fast lookup, frequency counting, deduplication |
| **Linked lists** | Pointer-style thinking without trees yet |
| **Stacks & queues** | LIFO/FIFO; previews graph BFS later |
| **Recursion (intro)** | Base case + recursive case; small depth only |
| **Binary search (intro)** | Sorted arrays; pairs well with arrays phase |
| **Sorting awareness** | Know what built-in `sort` does; optional hand-run of merge/quick at high level |

#### ⏭️ Defer to Intermediate Track (do not rush these as a beginner)

| Topic | Why we wait |
| --- | --- |
| **Trees & BSTs** | Need solid recursion and pointer comfort |
| **Graphs (BFS/DFS)** | Need trees and queue/stack fluency |
| **Dynamic programming** | Needs recursion, patterns, and subproblem intuition |
| **Backtracking / greedy (heavy)** | Tied to trees, graphs, and DP patterns |

If a lesson in the course touches trees or DP lightly, **watch for intuition** but prioritize the in-scope topics above.

---

### 6. Bridge practice (still beginner-level)

Before moving up, consolidate with **easy** problems that mix:

- Arrays / strings (two pointers, prefix ideas at easy level)
- Hashing
- Stack / queue simulation
- Simple recursion (factorial-style, not DP tables)

Suggested platforms: NeetCode easy list (arrays/hash only), HackerRank easy, or LeetCode easy filtered by tags above.

**Target:** ~20–30 focused easies with written complexity notes after each solve.

---

## 🏁 Weekly contest (beginner division)

Each week on cohort **contest day**, solve the **beginner division** of the Codeforces mashup — problems only use concepts your track has covered so far (e.g. arrays/hash early in the bootcamp; stacks/queues later).

Details and schedule: [Bootcamp Events](../Bootcamp%20Events/README.md).

---

## 🎓 End-of-bootcamp goals (beginner cohort)

By the end of the summer you should be able to:

- Implement solutions in **Python** without fighting syntax
- State time/space complexity for your approach
- Solve most **easy** array/hash/stack/queue problems in one sitting
- Explain recursion with a base case and a shrinking subproblem

You do **not** need trees, graphs, or DP on this track. If you applied at the wrong level, talk to mentors — the [Intermediate](../Intermediate%20Track/README.md) and [Advanced](../Advanced%20Track/README.md) roadmaps describe **other cohorts**, not your required next step.

---

> *DSA is an art, and consistency is the brush. 💫✨*

**Cohort events:** [Bootcamp Events](../Bootcamp%20Events/README.md)
