---
title: "On the parameterized complexity of interval scheduling with eligible machine sets"
collection: publications
category: manuscripts 
permalink: /publication/Unrelated Machines
excerpt: 'https://doi.org/10.1016/j.jcss.2024.103533'
date: 2024-09-01
venue: 'Journal of Computer and System Sciences, 144, p.103533.'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1016/j.jcss.2024.103533'
bibtexurl: 'https://yuvalyitz.github.io/home/files/hermelin2024parameterized.bib'
citation: 'Hermelin, D., Itzhaki, Y., Molter, H. and Shabtay, D., 2024. On the parameterized complexity of interval scheduling with eligible machine sets. Journal of Computer and System Sciences, 144, p.103533.'
---
We provide new parameterized complexity results for Interval Scheduling on Eligible Machines. In this problem, a set of n jobs is given to be processed non-preemptively on a set of m machines. Each job has a processing time, a deadline, a weight, and a set of eligible machines that can process it. The goal is to find a maximum weight subset of jobs that can each be processed on one of its eligible machines such that it completes exactly at its deadline. We focus on two parameters: The number m of machines, and the largest processing time $p_{\max}$. Our main contribution is showing W[1]-hardness when parameterized by m. This answers Open Problem 8 of Mnich and van Bevern's list of 15 open problems in parameterized complexity of scheduling problems [Computers & Operations Research, 2018]. Furthermore, we show NP-hardness even when $p_{\max}=O(1)$ and present an FPT-algorithm with for the combined parameter $p_{\max}+m$.
