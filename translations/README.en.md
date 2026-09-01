<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="../images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Algorithms and Data Structures Guide</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadealgoritmos?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadealgoritmos?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadealgoritmos?style=flat-square" alt="Last commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadealgoritmos?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Complete Algorithms and Data Structures guide: learning paths, courses, books, channels, tools and communities
> to get into the field and grow. Last review: September 2026.
>
> This is a translation of the Brazilian Portuguese guide. Resources are curated for the Brazilian community, so many are in Portuguese; 🇺🇸 marks English-language content.

## 🌍 Languages
[🇧🇷 Português](../README.md) · 🇺🇸 English (you are here)

## 📚 Table of contents
- [🎯 About this guide](#-about-this-guide)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Where to start](#-where-to-start)
- [🎓 Free courses](#-free-courses)
- [💰 Paid courses](#-paid-courses)
- [📖 Documentation and handouts](#-documentation-and-handouts)
- [📚 Books](#-books)
- [🎥 YouTube channels](#-youtube-channels)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs and newsletters](#-sites-blogs-and-newsletters)
- [🛠️ Tools](#-tools)
- [🧪 Hands-on projects and challenges](#-hands-on-projects-and-challenges)
- [🏆 Competitive programming](#-competitive-programming)
- [👁️ Visualizers](#-visualizers)
- [🤖 AI in practice](#-ai-in-practice)
- [📜 Certifications](#-certifications)
- [💼 Career and jobs](#-career-and-jobs)
- [👥 Communities](#-communities)
- [🚨 How to contribute](#-how-to-contribute)
- [📄 License](#-license)
- [💙 Support the project](#-support-the-project)

## 🎯 About this guide
Algorithms are precise recipes for solving problems; data structures are the ways of organizing information so those recipes run fast. Together they are the part of programming that **does not change when the framework changes**: the same `HashMap`, the same binary search and the same Dijkstra sit behind the database, the GPS, the compiler and the social network feed. They are also the central topic of big-tech technical interviews and what separates "it works" from "it works with a million users".

This guide is for people who are starting out (know the basics of some language) and for people who already program but never studied the topic in a structured way. **Portuguese and free** resources come first in every section; 💰 marks paid content, 🇺🇸 English-language content and 🆕 material published or updated between 2024 and 2026. Every link was verified on the date of the last review.

## 🗺️ Roadmap
- [roadmap.sh — Data Structures and Algorithms](https://roadmap.sh/datastructures-and-algorithms) — Community-made visual, interactive roadmap: complexity, structures, sorting, graphs and DP, with links per topic. 🇺🇸
- [roadmap.sh — Computer Science](https://roadmap.sh/computer-science) — Computer Science curriculum for self-taught developers; algorithms and data structures are its backbone. 🇺🇸
- [Coding Interview University (tradução PT-BR)](https://github.com/jwasham/coding-interview-university/blob/main/translations/README-ptbr.md) — Complete CS study plan that got its author a job at Amazon: topic order, videos and readings, translated into Portuguese.
- [NeetCode Roadmap](https://neetcode.io/roadmap) — Dependency tree between topics (arrays → two pointers → ... → DP) with hand-picked problems for each node. 🇺🇸
- [OSSU — Computer Science](https://github.com/ossu/computer-science) — Complete free CS degree built from open courses; its algorithms track uses Princeton and MIT. 🇺🇸
- [kelvins/algorithms-and-data-structures](https://github.com/kelvins/algorithms-and-data-structures) — Brazilian repository with algorithms and data structures implemented in several languages, organized by topic — great for seeing the same algorithm in C, Python, Java and Go.

**Summary path** (follow in order; each step has resources in the sections below):

1. **Logic and one language** — variables, conditionals, loops, functions and recursion in Python, C, Java or JavaScript. Without this, nothing else makes sense.
2. **Complexity** — Big-O notation, O(1)/O(log n)/O(n)/O(n log n)/O(n²), time × space, analyzing loops and recurrences.
3. **Linear structures** — arrays, strings, linked lists, stacks, queues and deques; two pointers and sliding window.
4. **Searching and sorting** — binary search; bubble/insertion/selection to understand, merge sort, quick sort and heap sort to use; linear-time sorting.
5. **Hashing** — hash tables, `dict`/`HashMap`/`Map`, collisions and when O(1) lies.
6. **Trees and heaps** — binary trees, BST, traversals, balanced trees (AVL/red-black, concept only), heaps and priority queues, tries.
7. **Graphs** — representation, BFS/DFS, topological sort, Dijkstra, union-find, minimum spanning tree.
8. **Design techniques** — recursion and backtracking, divide and conquer, greedy and dynamic programming.
9. **Advanced (optional)** — segment trees and Fenwick, string algorithms (KMP, Z, suffix structures), network flow, NP-completeness.

## 🚀 Where to start
1. **Learn to program first.** If you don't yet, take Curso em Vídeo's [Curso de Algoritmos e Lógica de Programação](https://www.youtube.com/playlist?list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV) or USP's [Introdução à Ciência da Computação com Python](https://www.coursera.org/learn/ciencia-computacao-python-conceitos) (both in Portuguese).
2. **Understand Big-O in an afternoon:** read [Notação Big O explicada com exemplos](https://www.freecodecamp.org/portuguese/news/notacao-big-o-explicada-com-exemplos/) (Portuguese) and bookmark the [Big-O Cheat Sheet](https://www.bigocheatsheet.com/).
3. **Read a light book:** [Entendendo Algoritmos](https://novatec.com.br/livros/entendendo-algoritmos-2ed/) (illustrated, Portuguese edition of *Grokking Algorithms*) is the best first book in the field.
4. **Take a complete course in Portuguese:** [Estrutura de Dados em C (Programação Descomplicada)](https://www.youtube.com/playlist?list=PL8iN9FQ7_jt6H5m4Gm0H89sybzR9yaaka), [Estrutura de Dados e Algoritmos Java (Loiane)](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrgumpzz-l8kFMw2DLERdxi) or the [UNIVESP](https://www.youtube.com/playlist?list=PLxI8Can9yAHf8k8LrUePyj0y3lLpigGcl) course.
5. **Watch every structure in action** on [VisuAlgo](https://visualgo.net/en) and step through your own code on [Python Tutor](https://pythontutor.com/).
6. **Implement it yourself** — linked list, stack, queue, BST, heap and hash table, from scratch, no libraries — and compare with [kelvins/algorithms-and-data-structures](https://github.com/kelvins/algorithms-and-data-structures).
7. **Practice every day:** start with the easy problems on [HackerRank](https://www.hackerrank.com/domains/data-structures) and [Neps Academy](https://neps.academy/br); then the [CSES Problem Set](https://cses.fi/problemset/) by topic.
8. **Go deeper with MIT:** [6.006 Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) is the definitive course — and, if the goal is interviews, move on to the [NeetCode Roadmap](https://neetcode.io/roadmap).

Your first "real" algorithm — binary search in Python, O(log n):

```python
def binary_search(items, target):
    lo, hi = 0, len(items) - 1
    while lo <= hi:
        mid = (lo + hi) // 2
        if items[mid] == target:
            return mid             # found: return the position
        if items[mid] < target:
            lo = mid + 1           # target is to the right
        else:
            hi = mid - 1           # target is to the left
    return -1                      # not in the list

print(binary_search([2, 5, 8, 12, 16, 23, 38, 56, 72, 91], 23))  # 5
```

On a sorted list of 1 million items, linear search makes up to 1,000,000 comparisons; binary search makes at most 20. That difference is the reason to study this guide.

## 🎓 Free courses
### In Portuguese
- [Curso de Algoritmos e Lógica de Programação (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV) — Gustavo Guanabara's course for people who have never programmed: variables, conditionals, loops and arrays in plain Portuguese.
- [UNIVESP — Estrutura de Dados (Engenharia de Computação)](https://www.youtube.com/playlist?list=PLxI8Can9yAHf8k8LrUePyj0y3lLpigGcl) — Complete course from the São Paulo public virtual university on YouTube: lists, stacks, queues, trees and graphs.
- [UNICAMP — MC202 Estruturas de Dados (aulas gravadas)](https://www.youtube.com/playlist?list=PL5TPkym335qzgzl0jW6Xf4XITmCofzOCy) — Recorded MC202 lectures from UNICAMP's Institute of Computing collected in a playlist.
- [UNICAMP — MC202 Estruturas de Dados (slides e vídeos do Prof. Rafael Schouery)](https://www.ic.unicamp.br/~rafael/mc202.html) — Professor's page with slides for every lecture and matching videos, in C: pointers, lists, trees, hashing and graphs.
- [UNICAMP — MC102 Algoritmos e Programação de Computadores](https://www.ic.unicamp.br/~mc102/) — Open material from UNICAMP's introductory course: slides, exercises and references for beginners.
- [USP e-Aulas — Algoritmos e Estruturas de Dados (PCS3110)](https://eaulas.usp.br/portal/course.action?course=8049) — 49 videos by Prof. Romero Tori (Poli-USP): algorithm analysis, lists, hashing, heaps, sorting and graphs.
- [Coursera — Introdução à Ciência da Computação com Python Parte 1 (USP)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos) — USP course teaching logic and basic algorithms in Python; free to audit (certificate is paid).
- [Coursera — Introdução à Ciência da Computação com Python Parte 2 (USP)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos-2) — Continuation: recursion, sorting, searching and complexity, still aimed at beginners.
- [Estrutura de Dados em Linguagem C — Curso Completo (Programação Descomplicada)](https://www.youtube.com/playlist?list=PL8iN9FQ7_jt6H5m4Gm0H89sybzR9yaaka) — Over 100 lessons by Prof. André Backes (UFU) implementing every structure in C from scratch.
- [Curso Estrutura de Dados e Algoritmos Java (Loiane Groner)](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrgumpzz-l8kFMw2DLERdxi) — Free course with certificate: stacks, queues, lists, trees, sorting and searching in Java, with code on GitHub.
- [Repositório do curso de Estrutura de Dados e Algoritmos Java](https://github.com/loiane/estrutura-dados-algoritmos-java) — Source code for each of Loiane's lessons, organized by structure.
- [Estrutura de Dados (Programação Dinâmica)](https://www.youtube.com/playlist?list=PL5TJqBvpXQv5Bb71AE5Cd_kB5rNsfU4Cp) — Playlist from Kizzy Terra and Hallison Paz's channel explaining structures with Python and strong visual teaching.
- [Estruturas de Dados e Algoritmos (Bóson Treinamentos)](https://www.youtube.com/playlist?list=PLucm8g_ezqNpHdoSlPrLMB1Ga8dBrNRsz) — Fábio dos Reis' series with concepts and step-by-step implementations.
- [Aprenda Estrutura de Dados e Algoritmos (DIO)](https://www.dio.me/courses/aprenda-o-que-sao-estrutura-de-dados-e-algoritmos) — Free course with certificate: lists, stacks, queues, trees, hash tables and graphs.
- [Curso de Estrutura de Dados (Cursa)](https://cursa.com.br/curso-de-estrutura-de-dados/207) — Free online course with a digital certificate on completion, theory and practice.
- [Neps Academy](https://neps.academy/br) — Free Brazilian platform with tracks on algorithms, data structures and competitive programming, with a built-in online judge.
- [Introdução à Programação Competitiva (Neps Academy)](https://neps.academy/br/course/introducao-a-programacao-competitiva) — Neps' entry course: how online judges work, input parsing, complexity and first problems.

### In English
- [MIT 6.006 — Introduction to Algorithms (OCW, 2020)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) — The world's most famous algorithms course, with videos, notes, problem sets and solved exams. 🇺🇸
- [MIT 6.006 — playlist das aulas no YouTube](https://www.youtube.com/playlist?list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY) — All 32 lectures of 6.006 (2020) on the official MIT OpenCourseWare channel. 🇺🇸
- [MIT 6.046J — Design and Analysis of Algorithms (OCW)](https://ocw.mit.edu/courses/6-046j-design-and-analysis-of-algorithms-spring-2015/) — Sequel to 6.006: divide and conquer, advanced DP, network flow, NP-completeness and approximation algorithms. 🇺🇸
- [MIT 6.042J — Mathematics for Computer Science (OCW)](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-spring-2015/) — The discrete math behind algorithms: proofs, induction, graphs, counting and probability. 🇺🇸
- [Algorithms, Part I (Princeton — Coursera)](https://www.coursera.org/learn/algorithms-part1) — Sedgewick and Wayne's course: union-find, sorting, balanced trees and hashing in Java; free to audit. 🇺🇸
- [Algorithms, Part II (Princeton — Coursera)](https://www.coursera.org/learn/algorithms-part2) — Continuation: graphs, shortest paths, max flow, strings and compression. 🇺🇸
- [Algorithms Specialization (Stanford — Coursera)](https://www.coursera.org/specializations/algorithms) — Four courses by Tim Roughgarden focused on analysis and design; auditing is free, the certificate is paid. 🇺🇸
- [Data Structures and Algorithms Specialization (UC San Diego — Coursera)](https://www.coursera.org/specializations/data-structures-algorithms) — Hands-on specialization with an autograder in several languages, from basics to advanced strings and graphs. 🇺🇸
- [Khan Academy — Algorithms](https://www.khanacademy.org/computing/computer-science/algorithms) — Gentle introduction (with Dartmouth) to binary search, sorting, recursion and graphs, with interactive exercises. 🇺🇸
- [CS50x 2026 (Harvard)](https://cs50.harvard.edu/x/) — Harvard's introduction to Computer Science; the C, algorithms and data structures weeks are the perfect foundation. 🆕 🇺🇸
- [Data Structures Easy to Advanced (William Fiset — freeCodeCamp)](https://www.youtube.com/watch?v=RBSGKlAvoiM) — 8 hours of a Google engineer implementing every structure, with complexity analysis. 🇺🇸
- [Algorithms and Data Structures Tutorial — Full Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=8hly31xKli0) — 5-hour beginner course, in Python, covering search, sorting, lists, trees and graphs. 🇺🇸
- [Codeforces EDU (ITMO Academy)](https://codeforces.com/edu/courses) — Free video courses with problems: binary search, two pointers, segment trees, suffix structures and more. 🇺🇸
- [USACO Guide](https://usaco.guide/) — Free, complete competitive programming track (Bronze → Platinum) with problems for each module. 🇺🇸
- [Intro to Algorithms (Udacity)](https://www.udacity.com/course/intro-to-algorithms--cs215) — Free course that uses social networks as the thread to teach graphs and algorithm analysis. 🇺🇸

## 💰 Paid courses
- [Learn Data Structures and Algorithms with Python (Codecademy)](https://www.codecademy.com/learn/learn-data-structures-and-algorithms-with-python) — Interactive in-browser track, with a certificate on the Pro plan. 💰 🇺🇸
- [Grokking the Coding Interview Patterns (Educative)](https://www.educative.io/courses/grokking-coding-interview) — Teaches the ~20 patterns that solve most interview questions (sliding window, two pointers, etc.). 🆕 💰 🇺🇸
- [AlgoExpert](https://www.algoexpert.io/) — 160+ questions with video explanations and a coding workspace, aimed at interviews. 💰 🇺🇸
- [NeetCode Courses (Pro)](https://neetcode.io/courses) — Algorithms, advanced DP and system design courses from the creator of NeetCode 150. 💰 🇺🇸
- [Data Structures and Algorithms Nanodegree (Udacity)](https://www.udacity.com/course/data-structures-and-algorithms-nanodegree--nd256) — Program with mentor-reviewed projects, in Python. 💰 🇺🇸

## 📖 Documentation and handouts
- [Projeto de Algoritmos em linguagem C (Paulo Feofiloff, IME-USP)](https://www.ime.usp.br/~pf/algoritmos/) — Classic free IME-USP handout: recursion, searching, sorting, lists, trees and graphs in C, with exercises.
- [Curso de Análise de Algoritmos (Paulo Feofiloff, IME-USP)](https://www.ime.usp.br/~pf/analise_de_algoritmos/) — Lecture notes in Portuguese on asymptotic notation, recurrences, optimal sorting and dynamic programming.
- [Curso de Estruturas de Dados (Feofiloff, baseado em Sedgewick e Wayne)](https://www.ime.usp.br/~pf/estruturas-de-dados/) — Portuguese handout that follows Sedgewick and Wayne's *Algorithms*, with Java implementations.
- [Linguagem C Descomplicada — índice de Estrutura de Dados](https://programacaodescomplicada.wordpress.com/indice/estrutura-de-dados/) — Written index of Prof. André Backes' lessons, with the code for each structure.
- [Material de Programação Competitiva (UnBalloon — UnB)](https://github.com/UnBalloon/programacao-competitiva) — Portuguese tutorials from the UnB group on the techniques and structures used in the Maratona.
- [Livreto FACOMpetindo (UFMS)](https://facompetindo.gitbook.io/facompetindo) — Introductory Portuguese guide for competitions, focused on OBI, in C++ and Python.
- [NOIC — Materiais de Informática](https://noic.com.br/materiais-informatica/) — Written lessons in Portuguese for OBI, organized by level, maintained by former olympiad medalists.
- [Algorithms for Competitive Programming (cp-algorithms)](https://cp-algorithms.com/) — The technical reference for competitive programming: every algorithm with proof, code and problems. 🇺🇸
- [Algorithms, 4th Edition — booksite (Sedgewick e Wayne)](https://algs4.cs.princeton.edu/home/) — Princeton's book site with all the Java code, summaries and exercises for every chapter, free. 🇺🇸
- [DSA Tutorial (GeeksforGeeks)](https://www.geeksforgeeks.org/dsa/dsa-tutorial-learn-data-structures-and-algorithms/) — The DSA encyclopedia: an article for practically every algorithm, with code in several languages. 🇺🇸
- [Learn DSA (Programiz)](https://www.programiz.com/dsa) — Short, visual tutorials, great for a first pass over each structure. 🇺🇸
- [DSA Tutorial (W3Schools)](https://www.w3schools.com/dsa/) — Step-by-step tutorial with in-browser simulations and exercises. 🇺🇸
- [Big-O Cheat Sheet](https://www.bigocheatsheet.com/) — Time and space complexity table for the main structures and sorting algorithms. 🇺🇸
- [Study cheatsheets de algoritmos (Tech Interview Handbook)](https://www.techinterviewhandbook.org/algorithms/study-cheatsheet/) — Per-topic summary of what shows up in interviews: pitfalls, techniques and essential problems. 🇺🇸

## 📚 Books
- [Entendendo Algoritmos — 2ª edição (Aditya Bhargava, Novatec)](https://novatec.com.br/livros/entendendo-algoritmos-2ed/) — The most recommended illustrated book for beginners, in Portuguese; new edition with trees, NP-completeness and Python 3. 🆕
- [Algoritmos: Teoria e Prática — 4ª edição (Cormen, Leiserson, Rivest e Stein, GEN)](https://www.grupogen.com.br/livro-algoritmos-thomas-cormen-9788595159907) — Official translation of CLRS, the bible of the field; 2024 edition with new chapters on bipartite graphs and machine learning. 🆕
- [Estruturas de Dados e Algoritmos com JavaScript — 2ª edição (Loiane Groner, Novatec)](https://novatec.com.br/livros/estruturas-de-dados-algoritmos-em-javascript-2ed/) — Every structure implemented in modern JavaScript, by a Brazilian author.
- [Lógica de Programação e Algoritmos com JavaScript — 2ª edição (Edécio Iepsen, Novatec)](https://novatec.com.br/livros/logica-programacao-algoritmos-com-javascript-2ed/) — For absolute beginners: logic, control structures and first algorithms with JavaScript.
- [Grokking Algorithms, 2nd Edition (Aditya Bhargava, Manning)](https://www.manning.com/books/grokking-algorithms-second-edition) — Original English edition of *Entendendo Algoritmos*, released in 2024. 🆕 🇺🇸
- [Algorithms, 4th Edition (Sedgewick e Wayne)](https://algs4.cs.princeton.edu/home/) — Princeton's textbook, with Java code and the Coursera course material. 🇺🇸
- [The Algorithm Design Manual (Steven Skiena)](https://www.algorist.com/) — Focused on *how* to design algorithms in practice, with a famous problem catalog. 🇺🇸
- [Algorithms (Jeff Erickson) — gratuito](https://jeffe.cs.illinois.edu/teaching/algorithms/) — Complete, free (Creative Commons) textbook from the University of Illinois, with hundreds of exercises. 🇺🇸
- [Open Data Structures (Pat Morin) — gratuito](https://opendatastructures.org/) — Open book on data structures, with Java, C++ and pseudocode editions. 🇺🇸
- [Competitive Programmer's Handbook (Antti Laaksonen) — gratuito](https://cses.fi/book/book.pdf) — Free PDF from the author: the reference book to get started in competitive programming, in C++. 🇺🇸
- [Competitive Programming 4 (Steven e Felix Halim)](https://cpbook.net/) — The most complete manual for ICPC-style contests, with thousands of classified problems. 💰 🇺🇸
- [Cracking the Coding Interview (Gayle Laakmann McDowell)](https://www.crackingthecodinginterview.com/) — 189 interview questions with solutions, and the big-tech process explained. 💰 🇺🇸
- [Elements of Programming Interviews (Aziz, Lee e Prakash)](https://elementsofprogramminginterviews.com/) — Harder collection than CtCI, with Python, Java and C++ versions. 💰 🇺🇸

## 🎥 YouTube channels
### In Portuguese
- [Curso em Vídeo](https://www.youtube.com/@CursoemVideo) — Gustavo Guanabara's channel; its Algorithms course is the entry point for millions of Brazilians.
- [Programação Dinâmica](https://www.youtube.com/@pgdinamica) — Kizzy Terra and Hallison Paz explain algorithms, structures and math with rare clarity.
- [Loiane Groner](https://www.youtube.com/@loianegroner) — Author of the JavaScript data structures book; complete free courses in Java.
- [Fabio Akita](https://www.youtube.com/@Akita) — Long, deep videos about computer science, hardware and the why of things.
- [Árvores: O Começo de TUDO | Estruturas de Dados e Algoritmos (Fabio Akita)](https://www.youtube.com/watch?v=9GdesxWtOgs) — Video from Akita's data structures trilogy: why trees are everywhere, from databases to compilers.
- [Programação Descomplicada](https://www.youtube.com/@progdescomplicada) — Prof. André Backes (UFU): C, data structures and algorithms, lesson by lesson.
- [Bóson Treinamentos](https://www.youtube.com/@bosontreinamentos) — Fábio dos Reis with courses on logic, C, Python and data structures.
- [Professor Douglas Maioli](https://www.youtube.com/@ProfessorDouglasMaioli) — Data structures course in C++ and programming videos for beginners.
- [UNIVESP](https://www.youtube.com/@univesptv) — Official channel of the São Paulo virtual university with entire recorded courses.
- [Neps Academy](https://www.youtube.com/@nepsacademy) — Lessons and competitive programming problem walkthroughs in Portuguese.
- [Big O Notation fácil de entender! (Attekita Dev)](https://www.youtube.com/watch?v=FR44uWofQ7o) — Time and space complexity explained in 15 minutes, with code examples.
- [Big O Notation — explicação para entrevistas (Augusto Galego)](https://www.youtube.com/watch?v=g-hIXvdDeZk) — How to talk about complexity in a technical interview, by someone who has interviewed at big tech.

### In English
- [Abdul Bari — Algorithms](https://www.youtube.com/playlist?list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O) — 80+ blackboard lessons covering an entire university algorithms course. 🇺🇸
- [mycodeschool — Data structures](https://www.youtube.com/playlist?list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P) — The classic data structures playlist in C/C++, still the clearest for lists, stacks and trees. 🇺🇸
- [WilliamFiset — Data structures playlist](https://www.youtube.com/playlist?list=PLDV1Zeh2NRsB6SWUrDFW2RmDotAfPbeHu) — Advanced structures (Fenwick, union-find, indexed heaps) with code on GitHub. 🇺🇸
- [NeetCode](https://www.youtube.com/@NeetCode) — Short, visual solutions to the most common interview problems. 🇺🇸
- [NeetCode — Leetcode BLIND-75 Solutions](https://www.youtube.com/playlist?list=PLot-Xpze53ldVwtstag2TL4HQhAnC8ATf) — The 75 most-asked interview questions, solved one by one. 🇺🇸
- [MIT OpenCourseWare](https://www.youtube.com/@mitocw) — Official channel with full 6.006, 6.046 and 6.042. 🇺🇸
- [Errichto Algorithms](https://www.youtube.com/@Errichto) — One of the world's top competitors teaching techniques and solving contests live. 🇺🇸
- [Reducible](https://www.youtube.com/@Reducible) — 3Blue1Brown-style animations for algorithms: FFT, DP, graphs and more. 🇺🇸
- [Back To Back SWE](https://www.youtube.com/@BackToBackSWE) — Long, careful explanations of interview problems, intuition before code. 🇺🇸
- [Colin Galen](https://www.youtube.com/@ColinGalen) — How to think in competitive programming: mindset, training and problem solving. 🇺🇸
- [Tushar Roy — Coding Made Simple](https://www.youtube.com/@tusharroy2525) — Dynamic programming and graphs explained with tables drawn step by step. 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech #186 — Algoritmos e estrutura de dados](https://www.hipsters.tech/algoritmos-e-estrutura-de-dados-hipsters-186/) — Episode with engineers from Amazon and other companies: do you really need algorithms to work as a programmer?
- [Fronteiras da Engenharia de Software](https://fronteirases.github.io/) — Brazilian podcast bringing researchers to talk about software engineering in accessible language.
- [ADSP: The Podcast (Algorithms + Data Structures = Programs)](https://adspthepodcast.com/) — Conor Hoekstra and Bryce Lelbach talk weekly about algorithms, languages and libraries. 🇺🇸
- [Lex Fridman Podcast — Donald Knuth](https://lexfridman.com/donald-knuth/) — Conversation with the author of *The Art of Computer Programming* about algorithms, TeX and life. 🇺🇸
- [CoRecursive](https://corecursive.com/) — Behind-the-scenes software stories, several about algorithms and structures that changed the industry. 🇺🇸

## 📰 Sites, blogs and newsletters
- [Meus cursos gratuitos favoritos para aprender estruturas de dados e algoritmos a fundo (freeCodeCamp PT)](https://www.freecodecamp.org/portuguese/news/meus-cursos-gratuitos-favoritos-para-aprender-estruturas-de-dados-e-algoritmos-a-fundo/) — Article in Portuguese comparing the best open DSA courses.
- [Notação Big O explicada com exemplos (freeCodeCamp PT)](https://www.freecodecamp.org/portuguese/news/notacao-big-o-explicada-com-exemplos/) — O(1), O(n), O(log n) and O(n²) with code examples, in Portuguese.
- [freeCodeCamp PT — tag Algoritmos](https://www.freecodecamp.org/portuguese/news/tag/algoritmos/) — All of freeCodeCamp's translated articles about algorithms.
- [O que são estruturas de dados? (Alura)](https://www.alura.com.br/artigos/estruturas-de-dados-introducao) — Portuguese introduction to structures and algorithms, with everyday examples.
- [NOIC — Informática](https://noic.com.br/informatica/) — News, materials and mock exams for the Brazilian Informatics Olympiad.
- [Code Marathon — Como estudar para a Maratona de Programação](https://www.codemarathon.com.br/conteudos/introducao/como-estudar-para-maratona-de-programacao) — Brazilian site with a study path and content for the SBC Maratona.
- [interviewing.io — Blog](https://interviewing.io/blog) — Real data from thousands of technical interviews: what works and what doesn't. 🇺🇸
- [Hello Interview — Data Structures and Algorithms](https://www.hellointerview.com/learn/code) — DSA interview guide written by former Meta and Amazon interviewers. 🆕 🇺🇸
- [DEV Community — tag #algorithms](https://dev.to/t/algorithms) — Community articles about algorithms, many in Portuguese. 🇺🇸
- [Lista de algoritmos (Wikipedia)](https://en.wikipedia.org/wiki/List_of_algorithms) — Encyclopedic catalog by area — to discover that the algorithm you need already exists. 🇺🇸

## 🛠️ Tools
- [Visual Studio Code](https://code.visualstudio.com/) — Free editor with a debugger for C, C++, Python, Java and JavaScript — stepping through code is the best way to understand an algorithm. 🇺🇸
- [Competitive Programming Helper (cph) — extensão do VS Code](https://github.com/agrawal-d/cph) — Runs the problem's test cases with one click and imports problems from online judges. 🇺🇸
- [LeetCode — extensão do VS Code](https://github.com/LeetCode-OpenSource/vscode-leetcode) — Solve and submit LeetCode problems without leaving the editor. 🇺🇸
- [Compiler Explorer (godbolt)](https://godbolt.org/) — See the assembly the compiler generates and understand why one implementation is faster than another. 🇺🇸
- [OnlineGDB](https://www.onlinegdb.com/) — Online compiler and debugger for C/C++, Python, Java and others; handy for testing without installing anything. 🇺🇸
- [Python Tutor](https://pythontutor.com/) — Runs your code step by step showing memory: pointers, call stack and recursion become visible. 🇺🇸
- [AtCoder Library (ACL)](https://github.com/atcoder/ac-library) — AtCoder's official C++ library with ready-made structures: segment tree, DSU, flow, strings. 🇺🇸
- [online-judge-tools (oj)](https://github.com/online-judge-tools/oj) — CLI that downloads test cases, generates random cases and tests your solution against a brute force. 🇺🇸
- [Hypothesis (Python)](https://hypothesis.readthedocs.io/en/latest/) — Property-based testing: generates thousands of inputs to find the case where your algorithm breaks. 🇺🇸
- [fast-check (JavaScript/TypeScript)](https://fast-check.dev/) — The Hypothesis equivalent for JS/TS. 🇺🇸
- [CLion (JetBrains)](https://www.jetbrains.com/clion/) — C/C++ IDE with an excellent visual debugger; free for students. 💰 🇺🇸

## 🧪 Hands-on projects and challenges
Solving problems is the only way to truly learn algorithms. Start with judges that have easy problems sorted by topic; then implement structures from scratch and compare with the reference repositories.
- [HackerRank — Data Structures](https://www.hackerrank.com/domains/data-structures) — Problems per structure (arrays, lists, trees, heaps, tries) with progressive difficulty. 🇺🇸
- [HackerRank — Algorithms](https://www.hackerrank.com/domains/algorithms) — Algorithms track: sorting, searching, greedy, DP and graphs. 🇺🇸
- [CSES Problem Set](https://cses.fi/problemset/) — 300 classic problems organized by topic — the best set for structured training. 🇺🇸
- [AtCoder](https://atcoder.jp/) — Japanese judge with weekly beginner contests (ABC) and very high-quality problems. 🇺🇸
- [Kattis](https://open.kattis.com/) — Thousands of problems from real contests, many used in the Maratona and the ICPC. 🇺🇸
- [HackerEarth — Practice](https://www.hackerearth.com/practice/) — Per-topic practice tracks with tutorials before the problems. 🇺🇸
- [Codewars](https://www.codewars.com/) — Katas in dozens of languages; compare your solution with the top-voted ones after solving. 🇺🇸
- [CodeChef](https://www.codechef.com/) — Monthly contests and practice tracks, from beginner to advanced. 🇺🇸
- [Project Euler](https://projecteuler.net/) — Math problems that only yield to efficient algorithms — great for training complexity. 🇺🇸
- [Advent of Code](https://adventofcode.com/) — December calendar with 25 puzzles requiring parsing, graphs, DP and simulation; 2025 edition is up. 🆕 🇺🇸
- [CodinGame](https://www.codingame.com/start/) — Learn algorithms by programming bots and games, with rankings and multiplayer challenges. 🇺🇸
- [Rosalind](https://rosalind.info/problems/locations/) — Algorithm problems applied to bioinformatics — strings and graphs with a purpose. 🇺🇸
- [The Algorithms](https://the-algorithms.com/) — Open implementations of hundreds of algorithms in every popular language. 🇺🇸
- [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) — The most-starred Python algorithms repository; read, compare and contribute. 🇺🇸
- [TheAlgorithms/JavaScript](https://github.com/TheAlgorithms/JavaScript) — Same collection in JavaScript, with best practices and tests. 🇺🇸
- [TheAlgorithms/Java](https://github.com/TheAlgorithms/Java) — Same collection in Java. 🇺🇸
- [TheAlgorithms/C-Plus-Plus](https://github.com/TheAlgorithms/C-Plus-Plus) — Same collection in C++. 🇺🇸
- [javascript-algorithms (README em PT-BR)](https://github.com/trekhleb/javascript-algorithms/blob/master/README.pt-BR.md) — Algorithms and structures in JavaScript with explanations and links to go deeper, translated.
- [interactive-coding-challenges (donnemartin)](https://github.com/donnemartin/interactive-coding-challenges) — 120+ interview challenges in Jupyter Notebooks with unit tests and solutions. 🇺🇸
- [williamfiset/Algorithms](https://github.com/williamfiset/Algorithms) — Java implementations of everything that appears in William Fiset's videos. 🇺🇸
- [Build your own X](https://github.com/codecrafters-io/build-your-own-x) — Rebuild a database, a compiler or Git from scratch — algorithms and structures in real life. 🇺🇸

> Widely used platforms that are **not** linked here because they block automated link checkers (we could not confirm the page): LeetCode, Codeforces (main site), Beecrowd (formerly URI Online Judge) and SPOJ. Search for them by name — all remain active.

## 🏆 Competitive programming
Competitive programming is solving algorithmic problems against the clock. In Brazil, the path is the **OBI** (schools) and the **Maratona SBC de Programação** (universities), which qualifies for the world ICPC. Even if you never compete, training in this format is the most efficient preparation for technical interviews.
- [OBI — Olimpíada Brasileira de Informática](https://olimpiada.ic.unicamp.br/) — Official olympiad for primary, secondary and university students, organized by SBC and UNICAMP. 🆕
- [OBI — provas de anos anteriores](https://olimpiada.ic.unicamp.br/passadas/) — All past exams with answer keys — the best way to train for OBI.
- [Maratona SBC de Programação](https://maratona.sbc.org.br/) — The Brazilian university competition, qualifier for the ICPC; rules, dates and sites. 🆕
- [Maratona SBC — histórico e provas](https://maratona.sbc.org.br/hist/) — Exams and results from previous Maratona editions.
- [ICPC — International Collegiate Programming Contest](https://icpc.global/) — The world finals where the best Maratona teams go. 🇺🇸
- [Neps Academy — trilhas de competição](https://neps.academy/br) — Free courses on programming techniques, graphs, math and structures, with OBI problems.
- [Clube de Programação UPF — vídeo-oficinas](https://maratonaupf.github.io/videos/introducao-programacao-competitiva) — Video workshops from the University of Passo Fundo for anyone who wants to start competing.
- [Livreto FACOMpetindo (repositório)](https://github.com/FACOMpetindo/livreto) — Code and exercises in Python and C++ that accompany the UFMS booklet.
- [Codeforces EDU](https://codeforces.com/edu/courses) — ITMO Academy courses inside Codeforces, with problems to practice each technique. 🇺🇸
- [USACO Guide](https://usaco.guide/) — Complete free track, from Bronze to Platinum, with solved problems and theory. 🇺🇸
- [cp-algorithms](https://cp-algorithms.com/) — The technical reference for every algorithm used in contests. 🇺🇸
- [Competitive Programmer's Handbook (PDF gratuito)](https://cses.fi/book/book.pdf) — The book to get started, by the creator of CSES. 🇺🇸
- [How to test your solution in Competitive Programming (Errichto)](https://www.youtube.com/watch?v=JXTVOyQpSGM) — How to set up a *stress test* comparing your solution against a brute force on random inputs. 🇺🇸

## 👁️ Visualizers
Watching a tree rebalance or Dijkstra expand nodes is worth more than ten pages of text. Use the visualizers while you study each structure.
- [VisuAlgo](https://visualgo.net/en) — Animations of dozens of structures and algorithms (sorting, BST, heap, graphs, DP), with a training mode. 🇺🇸
- [Data Structure Visualization (David Galles, USF)](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html) — Classic visualizer: insert values and watch AVL trees, B-trees, heaps and hashing reorganize themselves. 🇺🇸
- [Python Tutor](https://pythontutor.com/) — Visualize the execution of your own code, including recursion and pointers, in Python, C, C++, Java and JavaScript. 🇺🇸
- [Pathfinding Visualizer](https://clementmihailescu.github.io/Pathfinding-Visualizer/) — Draw walls on a grid and compare Dijkstra, A*, BFS and DFS finding the path. 🇺🇸
- [Introduction to the A* Algorithm (Red Blob Games)](https://www.redblobgames.com/pathfinding/a-star/introduction.html) — The best interactive article on pathfinding: BFS → Dijkstra → A* with manipulable diagrams. 🇺🇸
- [CS Academy — Graph Editor](https://csacademy.com/app/graph_editor/) — Paste a problem's edge list and see the graph drawn instantly. 🇺🇸
- [HackerEarth — visualizador de ordenação](https://www.hackerearth.com/practice/algorithms/sorting/bubble-sort/visualize/) — Step-by-step animation of sorting algorithms, with the code alongside. 🇺🇸

## 🤖 AI in practice
AI assistants are great private algorithms tutors — and terrible substitutes for your own reasoning. The rule: **the AI explains, you implement; the AI suggests, the online judge decides.**

**For learning**
- Paste your implementation and ask: *"analyze the time and space complexity line by line, point out the bottleneck and say whether it can be improved without changing the algorithm"*. Then check against the [Big-O Cheat Sheet](https://www.bigocheatsheet.com/).
- Ask for the **same structure in two languages** (e.g. a hash table in C and in Python) and compare what changes — this separates the concept from the syntax.
- Ask for an **informal proof of correctness** (loop invariant, why binary search terminates) and try to find holes in the explanation.
- Asked for a ready-made solution? Then also ask for **three test cases that would break it** and run them on [Python Tutor](https://pythontutor.com/) to see where it fails.
- Use the AI as an exercise generator: *"five two-pointer problems, easy to hard, no solutions; only give me a hint if I ask"*.

**For work and training**
- Use [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) or [Claude Code](https://code.claude.com/docs/en/overview) to write **test-case generators** and *stress tests*: a naive O(n²) solution as the oracle, thousands of random inputs, compare outputs. It is exactly what [Errichto's video](https://www.youtube.com/watch?v=JXTVOyQpSGM) teaches — the AI just removes the grunt work.
- Ask for property-based tests with [Hypothesis](https://hypothesis.readthedocs.io/en/latest/) (Python) or [fast-check](https://fast-check.dev/) (JS/TS): "for any list, the output of my sort is a sorted permutation of the input".
- In production code, ask the AI to spot **structures that are wrong for the access pattern** (a list where a set belongs, a linear search inside a loop) — it is the most common performance bug and the easiest one for it to find.

**Limits and good practices**
- **Technical interviews forbid AI.** Google, Amazon, Meta and most Brazilian companies ask you to solve alone, explaining your reasoning out loud. If you can only solve it with AI, you can't solve it.
- **Contests forbid it too.** Since September 2024 Codeforces forbids using AI to generate the solution logic (only syntax autocomplete is tolerated); OBI, Maratona and ICPC follow the same line. Training with AI and competing without it is like training with floaties.
- Reasoning models already solve gold-medal-level problems — see the [OpenAI paper](https://arxiv.org/abs/2502.06807) and [LiveCodeBench](https://livecodebench.github.io/). This shifts what the market values: less "can recite Dijkstra", more "can pick the right structure, prove it correct and verify what the AI produced".
- AI gets complexity wrong with confidence (calls O(n²) code O(n log n)) and invents properties of structures. Verify with a counterexample or a runtime test.
- Do not paste proprietary code, customer data or hiring-process exams into tools without your company's policy.

**Tools and readings**
- [GitHub Copilot](https://github.com/features/copilot) — Autocomplete and chat in the editor; free for students and with a free plan. 🆕 🇺🇸
- [Cursor](https://cursor.com/) — VS Code-based editor with AI built into the workflow. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Terminal coding agent: explains complexity, generates tests and refactors implementations. 🆕 🇺🇸
- [Claude](https://claude.com/product/overview) — Anthropic's assistant; good for step-by-step explanations and correctness proofs. 🆕 🇺🇸
- [Competitive Programming with Large Reasoning Models (OpenAI, arXiv 2025)](https://arxiv.org/abs/2502.06807) — Paper showing reasoning models reaching gold-medal level in contests — read it to understand what AI already solves. 🆕 🇺🇸
- [LiveCodeBench](https://livecodebench.github.io/) — Benchmark evaluating LLMs on fresh LeetCode, AtCoder and Codeforces problems, contamination-free. 🆕 🇺🇸
- [AlphaCode 2 — relatório técnico (Google DeepMind)](https://storage.googleapis.com/deepmind-media/AlphaCode2/AlphaCode2_Tech_Report.pdf) — How DeepMind built an AI system to compete on Codeforces: massive generation + filtering by tests. 🇺🇸

## 📜 Certifications
There is no official Algorithms and Data Structures certification — not from a company, not from an industry body. What the market recognizes is **technical interview performance**, **medals and rankings** (OBI, Maratona SBC, Codeforces/AtCoder ratings) and **published projects**. The certificates below are course-completion or skills-test certificates: they help on a résumé but do not replace practice.
- [JavaScript Algorithms and Data Structures Certification (freeCodeCamp)](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8) — Free, well-known certification: hundreds of exercises and 5 algorithm projects in JavaScript. 🇺🇸
- [HackerRank Skills Certification — Problem Solving (Basic)](https://www.hackerrank.com/skills-verification/problem_solving_basic) — Free timed test on data structures and algorithms; the certificate goes on your profile. 🇺🇸
- [HackerRank Skills Certification — Problem Solving (Intermediate)](https://www.hackerrank.com/skills-verification/problem_solving_intermediate) — Intermediate level of the same test. 🇺🇸
- [Curso Estrutura de Dados e Algoritmos Java (Loiane) — com certificado](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrgumpzz-l8kFMw2DLERdxi) — Free Portuguese course that issues a completion certificate.
- [Aprenda Estrutura de Dados e Algoritmos (DIO) — com certificado](https://www.dio.me/courses/aprenda-o-que-sao-estrutura-de-dados-e-algoritmos) — Free completion certificate.
- [Algorithms, Part I (Princeton — Coursera) — certificado](https://www.coursera.org/learn/algorithms-part1) — Auditing is free; the Princeton certificate is paid. 💰 🇺🇸
- [Data Structures and Algorithms Specialization (UC San Diego — Coursera) — certificado](https://www.coursera.org/specializations/data-structures-algorithms) — Paid certificate for the specialization with an autograder. 💰 🇺🇸

## 💼 Career and jobs
Algorithms and data structures are the main criterion in interviews at Google, Amazon, Meta, Microsoft, Nubank, iFood, Mercado Livre and most startups that pay in dollars — almost always in the *coding interview* format: 45 minutes, 1–2 problems, complexity explained out loud. They also appear in the tests of Brazilian recruiting platforms. In Brazil, the Código Fonte TV survey has salary ranges by level; for big techs with offices in the country, Levels.fyi is the reference.
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Complete free technical interview guide: résumé, algorithms, behavioral and negotiation. 🇺🇸
- [Grind 75](https://www.techinterviewhandbook.org/grind75/) — Problem list customizable by weeks available and hours per week, by the author of Blind 75. 🇺🇸
- [Blind 75 (Best practice questions)](https://www.techinterviewhandbook.org/best-practice-questions/) — The 75 questions that cover the most-asked interview patterns. 🇺🇸
- [NeetCode 150](https://neetcode.io/practice) — List organized by topic, with a video solution for each problem. 🇺🇸
- [Coding Interview University](https://github.com/jwasham/coding-interview-university) — GitHub's most popular CS study plan for big-tech interviews. 🇺🇸
- [kdn251/interviews](https://github.com/kdn251/interviews) — Everything you need to know for the interview: algorithms, structures, Big-O and links per company. 🇺🇸
- [A Senior Engineer's Guide to FAANG Interviews (interviewing.io)](https://interviewing.io/guides/hiring-process) — How the Google, Meta, Amazon (and similar) process works, step by step. 🇺🇸
- [Google Careers — Our hiring process](https://www.google.com/about/careers/applications/how-we-hire/) — Google's official page explaining the stages, including coding interviews. 🇺🇸
- [Google Careers — Build your future: resources](https://www.google.com/about/careers/applications/buildyourfuture/resources/) — Official technical preparation materials recommended by Google. 🇺🇸
- [Amazon — Software Development Interview Topics](https://www.amazon.jobs/content/en/how-we-hire/interview-prep/software-development-topics) — Amazon's official list of topics: data structures, algorithms, complexity and design. 🇺🇸
- [interviewing.io](https://interviewing.io/) — Anonymous mock interviews with big-tech engineers; free to practice as interviewee in some formats. 🇺🇸
- [Pramp](https://www.pramp.com/) — Free peer mock interviews: you interview and get interviewed. 🇺🇸
- [Pesquisa Salarial de Programadores 2026 (Código Fonte TV)](https://pesquisa.codigofonte.com.br/2026) — Brazil's largest developer salary survey, filterable by level, language, state and contract type. 🆕
- [Salario.com.br — Desenvolvedor back-end](https://www.salario.com.br/profissao/desenvolvedor-back-end/) — Official salary floor and average (CAGED data) by role and region.
- [Levels.fyi](https://www.levels.fyi/) — Big-tech salaries and levels, including Brazilian offices. 🇺🇸
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — Global overview of languages, tools and salaries. 🆕 🇺🇸
- [Programathor](https://programathor.com.br/) — Tech jobs in Brazil filterable by language and level.
- [GeekHunter](https://www.geekhunter.com/pt) — Brazilian platform where companies make offers to devs; includes an algorithms coding test.
- [Coodesh](https://coodesh.com/) — Tech jobs in Brazil with standardized technical challenges.
- [Remotar](https://remotar.com.br/) — 100% remote jobs for Brazilians.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Back-end jobs posted as GitHub issues.
- [frontendbr/vagas](https://github.com/frontendbr/vagas) — Front-end jobs posted as GitHub issues.

## 👥 Communities
- [Neps Academy — comunidade](https://neps.academy/br) — Forum and ranking of the largest Brazilian competitive programming platform.
- [r/programacao](https://www.reddit.com/r/programacao/) — Portuguese-language programming subreddit.
- [TabNews](https://www.tabnews.com.br/) — Brazilian technical content community created by Filipe Deschamps.
- [He4rt Developers](https://heartdevs.com/) — Brazilian open source community with an active Discord and study groups.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Brazilian community with tips, courses, mentoring and jobs.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Directory of Brazilian Telegram groups, including competitive programming and languages.
- [Rocketseat — comunidade](https://www.rocketseat.com.br/) — One of Brazil's largest dev communities, with an open Discord.
- [Codeforces Discord](https://discord.com/invite/codeforces) — Codeforces community server for discussing problems and contests. 🇺🇸
- [r/codeforces](https://www.reddit.com/r/codeforces/) — Subreddit about contests, ratings and editorials. 🇺🇸
- [r/leetcode](https://www.reddit.com/r/leetcode/) — Interview reports, study lists and problem questions. 🇺🇸
- [r/algorithms](https://www.reddit.com/r/algorithms/) — Theoretical discussions about algorithms and complexity. 🇺🇸
- [r/cscareerquestions](https://www.reddit.com/r/cscareerquestions/) — Careers, interviews and negotiation at tech companies. 🇺🇸

## 🚨 How to contribute
Found a broken link, a new course or a tool that deserves to be here? Open an issue using the repository templates or send a pull request. Criteria: working link, legal content that is free or clearly marked as paid, with a one-line description. Details in [CONTRIBUTING.md](../CONTRIBUTING.md).

## 📄 License
This project is under the [MIT](../LICENSE) license. Made with 💙 by [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) and the [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil) community.

## 💙 Support the project
Star this repository and the [main guide](https://github.com/arthurspk/guiadevbrasil), share it with someone who is starting out and follow the project on social media:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
