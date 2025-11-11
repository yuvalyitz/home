---
title: "Hardness of Interval Scheduling on Unrelated Machines"
collection: publications
category: "Conference Paper"
permalink: /publication/hardness unrelated.md
excerpt: "We resolve two open problems by establishing W[1]-hardness and NP-completeness results for Interval Scheduling on Unrelated Machines."
date: 2022-12-14
venue: "17th International Symposium on Parameterized and Exact Computation (IPEC 2022)"
paperurl: "https://doi.org/10.4230/LIPIcs.IPEC.2022.18"
bibtexurl: "https://yuvalyitz.github.io/files/hermelin2022hardness.bib"
citation: "Hermelin, D., Itzhaki, Y., Molter, H., and Shabtay, D. (2022). *Hardness of Interval Scheduling on Unrelated Machines.* In *17th International Symposium on Parameterized and Exact Computation (IPEC 2022).* Leibniz International Proceedings in Informatics (LIPIcs), Vol. 249, pp. 18:1–18:16. Schloss Dagstuhl – Leibniz-Zentrum für Informatik."
---

We establish new **parameterized** and **classical hardness** results for *Interval Scheduling on Unrelated Machines* — a fundamental scheduling problem motivated by just-in-time manufacturing, where jobs must be completed exactly at their deadlines.

Given \( n \) jobs and \( m \) machines, each job has a deadline, a weight, and machine-dependent processing times.  
The objective is to maximize the total weight of jobs completed precisely at their deadlines, yielding a uniquely defined processing interval per job on each machine.

Our results show that the problem is **W[1]-hard when parameterized by the number of machines \(m\)**, even in the restricted setting of parallel machines with *eligible-machine* sets.  
This resolves **Open Problem 8** from Mnich and van Bevern’s 2018 list of open questions on parameterized complexity in scheduling.  

We further prove that the **unweighted** variant is **NP-complete**, settling an open problem posed by Sung and Vlach (*Journal of Scheduling*, 2005).

---

[View paper on LIPIcs](https://doi.org/10.4230/LIPIcs.IPEC.2022.18)  
[Download BibTeX](https://yuvalyitz.github.io/files/hermelin2022hardness.bib)
