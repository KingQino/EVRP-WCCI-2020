# EVRP-WCCI-2020

* [Benchmark dataset](https://mavrovouniotis.github.io/EVRPcompetition2020/)
  - some bugs in the benchmark
    - The instance `E-n30-k3.evrp` is a wrong named instance because it has 4 vhicles, so we should change the name of it to `E-n30-k4.evrp`
    - the results from the heuristic approaches are better than that obtained by the exact algorothms, which is really confusing.
* Approaches
  - [ ] Simple Genetic Algorithm
    - Improvement is needed
    - encoding scheme & operators
  - [ ] Sequence-based Selection Hyper-heuristic Algorithm

* Reference:
  - (Team 1) Variable Neighbourhood Search by D. Woller, V. Vavra, V. Kozak, M. Kulich
    - [code](https://github.com/wolledav/VNS-EVRP-2020)
    - [papers](http://imr.ciirc.cvut.cz/People/David)
    - latest manuscript, I cannot share here, caz this work of the team hasn't been published
  - (Team 3) Genetic Algorithm by V. Q. Hien, T. C. Dao, T. B. Thang, H. T. T, Binh
    - [code](https://github.com/NeiH4207/EVRP)
    - [paper](https://www.researchgate.net/profile/Cong-Dao-Tran/publication/360604653_A_greedy_search_based_evolutionary_algorithm_for_electric_vehicle_routing_problem/links/641d203a315dfb4ccea54309/A-greedy-search-based-evolutionary-algorithm-for-electric-vehicle-routing-problem.pdf)

