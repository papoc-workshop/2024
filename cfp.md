---
title: Call for Papers
---

# Call for Papers

Consistency is one of the fundamental issues of distributed computing. 
Beyond the well-known tension between Consistency, Availability, and Partition-tolerance, as captured by the CAP theorem, many nuanced consistency models and algorithms have been developed for different purposes. 
These consistency models have subtly different behaviour in practice, which translates to difficult choices between fault tolerance, performance, and programmability.
The issues and trade-offs are particularly vexing at scale, with a large number of processes or large shared databases, and in the presence of high latency and failure-prone networks, such as edge computing and peer-to-peer networks.

Since its inception in 2014, the PaPoC workshop series has brought together researchers and practitioners who seek to develop better techniques and a better understanding of consistency in distributed systems. 
We welcome contributions from a wide range of backgrounds: system development, distributed algorithms, concurrency, fault tolerance, databases, programming languages, blockchain, and verification. 
While there is no one universally best solution, we believe that by bringing together these perspectives, we can develop techniques that provide useful guarantees to applications, that are usable by application developers, and that satisfy real-world scalability, performance, and reliability requirements.

The workshop is looking for contributions on the following, and associated, topics:

* Techniques for scaling and improving the performance of strongly consistent systems (e.g., Paxos-like algorithms, state-machine replication protocols and distributed transactional systems).
* Techniques for weak and hybrid consistency (such as session guarantees, causal consistency, operational transformation, conflict-free replicated data types (CRDTs), invariant-preserving replicated data types, monotonic programming, state merging, operation commutativity, etc).
* Data consistency in geo-replicated, peer-to-peer, and edge computing systems.
* How to expose consistency vs. performance and scalability trade-offs in the programming model, and how to help developers choose.
* How to support composed operations spanning multiple objects (transactions, sagas, workflows).
* Techniques or tools to aid the development of replicated data (e.g., reasoning, analysis and verification of application programs using storage systems with various consistency models, visualization techniques for distributed dependencies or state merges, etc.).
* Formal methods for distributed systems dealing with strong/weak consistent data (such as techniques for verifying safety, liveness or consistency properties, convergence verification, etc.) 
* Implementation techniques and optimisations for replicated data types to improve fault tolerance, security, application-level invariants, metadata usage, and controlling divergence.
* Studies of performance, scalability, and programmability for the aforementioned systems.


## Details on submissions

The PaPoC workshop invites submissions of three types:

1. short papers (up to 6 pages excluding bibliography) with original contributions, experience reports, or work in progress reports (supported by initial validations);
2. full papers (up to 12 pages excluding bibliography) which may be concurrently submitted (or accepted) to other venues and do not have the option to be published in the ACM library;
3. lightning talk abstract, summarized in a maximum of 300 words, reporting preliminary or crazy ideas, new trends, recent experience or ongoing results.

For the short paper submissions, we will allow authors to submit longer proposals, under the clear understanding that PC members are only expected to read the first 6 pages. Lightning talk abstracts will be limited to 300 words to avoid defeating the nature of a lightning talk.

Submissions do not need to be anonymised. All submissions should be written in English and submitted in PDF format. Paper submissions will be handled by HotCRP.

Papers and abstracts will be distributed to the participants of the workshop. Authors of accepted **short-paper contributions** will have the opportunity to choose whether they want their papers published in the ACM Digital Library (along with papers from the other EuroSys workshops). Lightning talk abstracts and full papers will not be included in the ACM Digital Library.

At least one author of each accepted submission is expected to present their work at the workshop, and to be available for discussions.

## How to submit your work

Submissions should be made [via HotCRP](https://papoc24.hotcrp.com/).

All submissions should be written in English and provided in PDF format. 
We suggest that you use the [ACM template for LaTeX or MS Word](https://www.acm.org/publications/proceedings-template), but this is not required.

If using the LaTeX template, please rely on the document class below (which matches the [format used by EuroSys](https://github.com/papoc-workshop/2023/tree/main/welcome_acm_dl)). 
To anonymize your submission, just pass the `anonymous` option to `acmart.cls`.

	\documentclass[sigplan,review]{acmart}
	\renewcommand\footnotetextcopyrightpermission[1]{}
	\settopmatter{printfolios=true,printacmref=false}

In case of any questions, please contact the Program Chairs at [papoc23@hotcrp.com](mailto:papoc23@hotcrp.com).

## Important Dates

| Submission deadline   |February 8th, 2024|
|---|---|
| Notification date     |March 8th, 2024|
| Camera-Ready deadline |March 15th, 2024|
| Workshop              |April 22nd, 2024|

All deadline times are 23:59 hrs
[AoE](https://www.timeanddate.com/time/zones/aoe).
