---
title: "Automated Benchmark Generation for Object Constraint Language (OCL) with SMT-Based Verification"
collection: Publication
category: Journal
permalink: /publication/2026-ocl-benchmark-generation
excerpt: 'A machine learning-based approach to improve handoff decisions in cognitive radio networks by predicting signal deterioration and optimizing spectrum usage.'
date: 2026-05-18
venue: 'Journal of Object Technology (JOT)'
paperurl: 'to be appear'
citation: 'Ankit Jha, Rosemary Monahan, Hao Wu, “Automated Benchmark Generation for Object Constraint Language (OCL) with SMT-Based Verification”, Journal of Object Technology, Volume 25, no. 3 ( 2026), pp. 3:365-378, doi:10.5381/jot.2026.25.3.a28.'
---

OCL tools are growing but their evaluation still relies on small, manually selected and domain-specific examples. Existing OCL benchmarks typically lack scale, systematic coverage of OCL features and rarely verify whether constraints can hold simultaneously within a benchmark suite. This  makes rigorous tool comparison difficult. We present an automated framework for generating solver-verified OCL benchmark suites from UML/Ecore metamodels. The framework combines a library of over one hundred reusable constraint patterns, an adaptive coverage-guided generation engine and an SMT solver-based verification pipeline that labels each constraint as satisfiable (SAT) or unsatisfiable (UNSAT) under bounded semantics. Our framework ensures that only well-typed, semantically meaningful and solver-verified OCL constraints are generated. We evaluate the framework on ten UML/Ecore metamodels covering multiple OCL language features and generating 50–100 machine verified constraints per model which approximates the user-required constraints. We further use the generated benchmark to evaluate existing OCL tools from the literature, identify major research gaps such as complex string functions, nested quantifiers, conflicts in constraint and specific feature testing. These benchmark generation techniques will advance the state of the art through evaluation of existing and future tools.
