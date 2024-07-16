---
title: Crash reproduction difficulty, an initial assessment
authors:
- Boris Cherry
- Xavier Devroey
- Pouria Derakhshanfar
- Benoît Vanderose
date: '2020-12-01'
publishDate: '2024-07-16T21:11:16.386715Z'
publication_types:
- paper-conference
publication: "*Proceedings of the 19th Belgium-Netherlands Software Evolution Workshop
  (BENEVOL '20)*"
abstract: This study presents the initial step towards a thorough analysis of the
  difficulty to reproduce a crash using searchbased crash reproduction. Traditionally,
  code size and complexity are considered representative indicators of the difficulty
  for search-based approaches, like search-based unit test generation, to generate
  tests. However, unlike unit test generation, crash reproduction does not seek to
  cover a set of behaviors but instead to generate one or more tests exercising a
  specific behavior reproducing a given crash. In this context, there is no guarantee
  that the indicators used for unit testing are still valid for crash reproduction.
  In this study, we seek to identify such indicators by considering various code metrics,
  code smells, and change metrics. We report our effort to collect those metrics for
  JCRASHPACK, a state-of-the-art crash reproduction benchmark, and an initial assessment
  by considering metrics individually. Our results show that although JCRASHPACK is
  larger than benchmarks used in previous studies, additional crashes should be added
  to improve its diversity and representativeness, and that no individual metric can
  be used to characterize the difficulty to reproduce a crash.
tags:
- Change metrics
- Code quality
- Search-based crash reproduction
- Software measurement
url_pdf: https://ceur-ws.org/Vol-2912/paper7.pdf
---
