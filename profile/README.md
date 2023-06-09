## Hi there 👋

We offer a range of open-source libraries and tools to support [Knowledge-Based Configuration].

Our current list of libraries and tools includes the following:

1. [**hiconfit-core**] - A set of Maven-based libraries for High-Performance Knowledge Based Configuration Techniques. Three key libraries are:
   1. **ca-cdr** - a library for Consistency-based Algorithms for Conflict Detection and Resolution.
   2. **fma** - a library for Feature Model Testing and Debugging
   3. **configurator** - a compact knowledge-based configurator supporting Matrix Factorization Based Variable Value Heuristics
2. [**KBStatistics**] - a Java tool that calculates statistics of given knowledge bases
3. [**FMGenerator**] - a Java tool that generates synthesized feature models

Documentation of these libraries and tools can be found in [hiconfit.manleviet.info].

## Used by

**CA-CDR-V2** and **CECore** are used by the following projects:

1. [FMTesting] - A Eclipse plug-in for feature model testing and debugging
2. A Python implementation of **CA-CDR-V2**'s algorithms can be found in [FlamaPy]
3. A Restful Webservice for developing product configurators with the following state-of-art technologies:
    - Domain reduction - decreases options that a user can select on the basis of previous selections of the user
    - Matrix Factorization-based Configuration and Recommendation - identifies Value Variable Heuristics on the basis of user requirements
    - Reordering the order of component's options on the basis of the Value Variable Heuristic
    - Conflict and diagnosis detection

and also used in the following published papers:

1. A. Felfernig, V.M. Le, S. Lubos. Conjunctive Query Based Constraint Solving For Feature Model Configuration. In 12th Conference on Information Technology and Its Applications. CITA’23, Danang, Vietnam. 2023. (to appear) [[arXiv](https://arxiv.org/pdf/2304.13422.pdf)]
2. V.M. Le, C.V. Silva, A. Felfernig, T.N.T. Tran, J. Galindo, D. Benavides. FastDiagP: An Algorithm for Parallelized Direct Diagnosis. In 37th AAAI Conference on Artificial Intelligence. AAAI’23, Washington, DC, USA. 2023. (to appear)
3. V.M. Le, A. Felfernig, and T.N.T. Tran, Test Case Aggregation for Efficient Feature Model Testing, 26th ACM International Systems and Software Product Line Conference (SPLC 2022) - Volume B, 2022. [https://doi.org/10.1145/3503229.3547046](https://doi.org/10.1145/3503229.3547046)
4. V.M. Le, A. Felfernig, M. Uta, T.N.T. Tran, and C. Vidal, WipeOutR: Automated Redundancy Detection for Feature Models, 26th ACM International Systems and Software Product Line Conference (SPLC 2022), 2022. [https://doi.org/10.1145/3546932.3546992](https://doi.org/10.1145/3546932.3546992).
5. V.M. Le, A. Felfernig, T.N.T. Tran, M. Atas, M. Uta, D. Benavides, J. Galindo, DirectDebug: A software package for the automated testing and debugging of feature models, Software Impacts, Volume 9, 2021, 100085, ISSN 2665-9638, [https://doi.org/10.1016/j.simpa.2021.100085](https://doi.org/10.1016/j.simpa.2021.100085).
6. V.M. Le, A. Felfernig, M. Uta, D. Benavides, J. Galindo, and T.N.T. Tran, DirectDebug: Automated Testing and Debugging of Feature Models, 2021 IEEE/ACM 43rd International Conference on Software Engineering: New Ideas and Emerging Results (ICSE-NIER), 2021, pp. 81-85, doi: [https://doi.org/10.1109/ICSE-NIER52604.2021.00025](https://doi.org/10.1109/ICSE-NIER52604.2021.00025).

## Development team

- [Mẫn] (Graz University of Technology, Austria)
- [Tamim] (Graz University of Technology, Austria)

## Connect with us

- For more information about the projects, support requests, and technical questions, do not hesitate to contact us.
- Report and discuss issues on [CA-CDR-V2's GitHub] and [CECore's GitHub].
- We welcome contributions from anyone.

## Citing

If our implementations are utilised in your research, kindly cite the corresponding papers listed in the [References].

HiConfiT Logo created by [Freepik - Flaticon](https://www.flaticon.com/free-icons/hobby)

<!-- Links  -->
[hiconfit-core]: hiconfit-core
[CA-CDR-V2]: ca-cdr-v2
[CECore]: ce-core
[KBStatistics]: kbstatistics
[FMGen]: fm-gen
[Get packages]: get_packages
[Mẫn]: https://github.com/manleviet
[Tamim]: https://github.com/taburg
[CA-CDR-V2's GitHub]: https://github.com/manleviet/CA-CDR-V2/issues
[CECore's GitHub]: https://github.com/manleviet/CECore/issues
[References]: references
[FMTesting]: https://github.com/AIG-ist-tugraz/FMTesting
[FlamaPy]: https://flamapy.github.io

<!-- Links  -->
[Knowledge-Based Configuration]: https://en.wikipedia.org/wiki/Knowledge-based_configuration
[**hiconfit-core**]: https://github.com/HiConfiT/hiconfit-core
[**KBStatistics**]: https://github.com/HiConfiT/KBStatistics
[**FMGenerator**]: https://github.com/HiConfiT/FMGenerator
[hiconfit.manleviet.info]: http://hiconfit.manleviet.info
