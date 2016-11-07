# aima-swift

Swift code for the book *Artificial Intelligence: A Modern Approach.* You can use this in conjunction with a course on AI, or for study on your own. We're looking for [solid contributors](https://github.com/shyamalschandra/aima-swift/blob/master/CONTRIBUTING.md) to help.

## swiftthon 3.4

This code is in Swift 3.1. You can [install the latest Swift 3.0 version](https://www.swift.org/downloads).

## Structure of the Project

When complete, this project will have Swift code for all the pseudocode algorithms in the book. For each major topic, such as `logic`, we will have the following three files in the main branch:

- `logic.swift`: Implementations of all the pseudocode algorithms, and necessary support functions/classes/data.
- `logic.playground`: A Swift Playground that explains and gives examples of how to use the code.
- `tests/logic_test.swift`: A lightweight test suite, using `assert` statementsswift.

# Index of Code

Here is a table of algorithms, the figure, name of the code in the book and in the repository, and the file where they are implemented in the code. This chart was made for the third edition of the book and needs to be updated for the upcoming fourth edition. Empty implementations are a good place for contributors to look for an issue.


| **Figure** | **Name (in 3<sup>rd</sup> edition)** | **Name (in repository)** | **File**
|:--------|:-------------------|:---------|:-----------|
| 2.1     | Environment        | `Environment` | [`agents.swift`](../master/agents.swift) |
| 2.1     | Agent              | `Agent` | [`agents.swift`](../master/agents.swift) |
| 2.3     | Table-Driven-Vacuum-Agent | `TableDrivenVacuumAgent` | [`agents.swift`](../master/agents.swift) |
| 2.7     | Table-Driven-Agent | `TableDrivenAgent` | [`agents.swift`](../master/agents.swift) |
| 2.8     | Reflex-Vacuum-Agent | `ReflexVacuumAgent` | [`agents.swift`](../master/agents.swift) |
| 2.10    | Simple-Reflex-Agent | `SimpleReflexAgent` | [`agents.swift`](../master/agents.swift) |
| 2.12    | Model-Based-Reflex-Agent | `ReflexAgentWithState` | [`agents.swift`](../master/agents.swift) |
| 3       | Problem            | `Problem` | [`search.swift`](../master/search.swift) |
| 3       | Node               | `Node` | [`search.swift`](../master/search.swift) |
| 3       | Queue              | `Queue` | [`utils.swift`](../master/utils.swift) |
| 3.1     | Simple-Problem-Solving-Agent | `SimpleProblemSolvingAgent` | [`search.swift`](../master/search.swift) |
| 3.2     | Romania            | `romania` | [`search.swift`](../master/search.swift) |
| 3.7     | Tree-Search        | `tree_search` | [`search.swift`](../master/search.swift) |
| 3.7     | Graph-Search        | `graph_search` | [`search.swift`](../master/search.swift) |
| 3.11    | Breadth-First-Search        | `breadth_first_search` | [`search.swift`](../master/search.swift) |
| 3.14    | Uniform-Cost-Search        | `uniform_cost_search` | [`search.swift`](../master/search.swift) |
| 3.17    | Depth-Limited-Search | `depth_limited_search` | [`search.swift`](../master/search.swift) |
| 3.18    | Iterative-Deepening-Search | `iterative_deepening_search` | [`search.swift`](../master/search.swift) |
| 3.22    | Best-First-Search  | `best_first_graph_search` | [`search.swift`](../master/search.swift) |
| 3.24    | A\*-Search        | `astar_search` | [`search.swift`](../master/search.swift) |
| 3.26    | Recursive-Best-First-Search | `recursive_best_first_search` | [`search.swift`](../master/search.swift) |
| 4.2     | Hill-Climbing      | `hill_climbing` | [`search.swift`](../master/search.swift) |
| 4.5     | Simulated-Annealing | `simulated_annealing` | [`search.swift`](../master/search.swift) |
| 4.8     | Genetic-Algorithm  | `genetic_algorithm` | [`search.swift`](../master/search.swift) |
| 4.11    | And-Or-Graph-Search | `and_or_graph_search` | [`search.swift`](../master/search.swift)  |
| 4.21    | Online-DFS-Agent   | `online_dfs_agent` | [`search.swift`](../master/search.swift) |
| 4.24    | LRTA\*-Agent       | `LRTAStarAgent`    | [`search.swift`](../master/search.swift) |
| 5.3     | Minimax-Decision   | `minimax_decision` | [`games.swift`](../master/games.swift) |
| 5.7     | Alpha-Beta-Search  | `alphabeta_search` | [`games.swift`](../master/games.swift) |
| 6       | CSP                | `CSP` | [`csp.swift`](../master/csp.swift) |
| 6.3     | AC-3               | `AC3` | [`csp.swift`](../master/csp.swift) |
| 6.5     | Backtracking-Search | `backtracking_search` | [`csp.swift`](../master/csp.swift) |
| 6.8     | Min-Conflicts      | `min_conflicts` | [`csp.swift`](../master/csp.swift) |
| 6.11    | Tree-CSP-Solver    | `tree_csp_solver` | [`csp.swift`](../master/csp.swift) |
| 7       | KB                 | `KB` | [`logic.swift`](../master/logic.swift) |
| 7.1     | KB-Agent           | `KB_Agent` | [`logic.swift`](../master/logic.swift) |
| 7.7     | Propositional Logic Sentence | `Expr` | [`logic.swift`](../master/logic.swift) |
| 7.10    | TT-Entails         | `tt_entials` | [`logic.swift`](../master/logic.swift) |
| 7.12    | PL-Resolution      | `pl_resolution` | [`logic.swift`](../master/logic.swift) |
| 7.14    | Convert to CNF     | `to_cnf` | [`logic.swift`](../master/logic.swift) |
| 7.15    | PL-FC-Entails?     | `pl_fc_resolution` | [`logic.swift`](../master/logic.swift) |
| 7.17    | DPLL-Satisfiable?  | `dpll_satisfiable` | [`logic.swift`](../master/logic.swift) |
| 7.18    | WalkSAT            | `WalkSAT` | [`logic.swift`](../master/logic.swift) |
| 7.20    | Hybrid-Wumpus-Agent    |         |           |
| 7.22    | SATPlan            | `SAT_plan`  | [`logic.swift`](../master/logic.swift) |
| 9       | Subst              | `subst` | [`logic.swift`](../master/logic.swift) |
| 9.1     | Unify              | `unify` | [`logic.swift`](../master/logic.swift) |
| 9.3     | FOL-FC-Ask         | `fol_fc_ask` | [`logic.swift`](../master/logic.swift) |
| 9.6     | FOL-BC-Ask         | `fol_bc_ask` | [`logic.swift`](../master/logic.swift) |
| 9.8     | Append             |            |              |
| 10.1    | Air-Cargo-problem    |          |
| 10.2    | Spare-Tire-Problem |          |
| 10.3    | Three-Block-Tower  |          |
| 10.7    | Cake-Problem       |          |
| 10.9    | Graphplan          |          |
| 10.13   | Partial-Order-Planner |          |
| 11.1    | Job-Shop-Problem-With-Resources |          |
| 11.5    | Hierarchical-Search |          |
| 11.8    | Angelic-Search   |          |
| 11.10   | Doubles-tennis     |          |
| 13      | Discrete Probability Distribution | `ProbDist` | [`probability.swift`](../master/probability.swift) |
| 13.1    | DT-Agent           | `DTAgent` | [`probability.swift`](../master/probability.swift) |
| 14.9    | Enumeration-Ask    | `enumeration_ask` | [`probability.swift`](../master/probability.swift) |
| 14.11   | Elimination-Ask    | `elimination_ask` | [`probability.swift`](../master/probability.swift) |
| 14.13   | Prior-Sample       | `prior_sample` | [`probability.swift`](../master/probability.swift) |
| 14.14   | Rejection-Sampling | `rejection_sampling` | [`probability.swift`](../master/probability.swift) |
| 14.15   | Likelihood-Weighting | `likelihood_weighting` | [`probability.swift`](../master/probability.swift) |
| 14.16   | Gibbs-Ask           | `gibbs_ask`  | [`probability.swift`](../master/probability.swift) |
| 15.4    | Forward-Backward   | `forward_backward` | [`probability.swift`](../master/probability.swift) |
| 15.6    | Fixed-Lag-Smoothing | `fixed_lag_smoothing` | [`probability.swift`](../master/probability.swift) |
| 15.17   | Particle-Filtering | `particle_filtering` | [`probability.swift`](../master/probability.swift) |
| 16.9    | Information-Gathering-Agent |          |
| 17.4    | Value-Iteration    | `value_iteration` | [`mdp.swift`](../master/mdp.swift) |
| 17.7    | Policy-Iteration   | `policy_iteration` | [`mdp.swift`](../master/mdp.swift) |
| 17.7    | POMDP-Value-Iteration  |           |        |
| 18.5    | Decision-Tree-Learning | `DecisionTreeLearner` | [`learning.swift`](../master/learning.swift) |
| 18.8    | Cross-Validation   | `cross_validation` | [`learning.swift`](../master/learning.swift) |
| 18.11   | Decision-List-Learning | `DecisionListLearner` | [`learning.swift`](../master/learning.swift) |
| 18.24   | Back-Prop-Learning | `BackPropagationLearner` | [`learning.swift`](../master/learning.swift) |
| 18.34   | AdaBoost           | `AdaBoost` | [`learning.swift`](../master/learning.swift) |
| 19.2    | Current-Best-Learning |          |
| 19.3    | Version-Space-Learning |          |
| 19.8    | Minimal-Consistent-Det |          |
| 19.12   | FOIL               |          |
| 21.2    | Passive-ADP-Agent  | `PassiveADPAgent` | [`rl.swift`](../master/rl.swift) |
| 21.4    | Passive-TD-Agent   | `PassiveTDAgent` | [`rl.swift`](../master/rl.swift) |
| 21.8    | Q-Learning-Agent   | `QLearningAgent` | [`rl.swift`](../master/rl.swift) |
| 22.1    | HITS               |         |         |
| 23      | Chart-Parse        | `Chart` | [`nlp.swift`](../master/nlp.swift) |
| 23.5    | CYK-Parse          | `CYK_parse` | [`nlp.swift`](../master/nlp.swift) |
| 25.9    | Monte-Carlo-Localization|       |


# Index of data structures

Here is a table of the implemented data structures, the figure, name of the implementation in the repository, and the file where they are implemented.

| **Figure** | **Name (in repository)** | **File** |
|:-----------|:-------------------------|:---------|
| 3.2    | romania_map              | [`search.swift`](../master/search.swift)   |
| 4.9    | vacumm_world             | [`search.swift`](../master/search.swift)   |
| 4.23   | one_dim_state_space      | [`search.swift`](../master/search.swift)   |
| 6.1    | australia_map            | [`search.swift`](../master/search.swift)   |
| 7.13   | wumpus_world_inference   | [`logic.swift`](../master/login.swift)   |
| 7.16   | horn_clauses_KB          | [`logic.swift`](../master/logic.swift)   |
| 17.1   | sequential_decision_environment | [`mdp.swift`](../master/mdp.swift)   |
| 18.2   | waiting_decision_tree    | [`learning.swift`](../master/learning.swift)   |


# Acknowledgements

Many thanks for contributions over the years. I got bug reports, corrected code, and other support from Darius Bacon, Phil Ruggera, Peng Shao, Amit Patil, Ted Nienstedt, Jim Martin, Ben Catanzariti, and others. Now that the project is on GitHub, you can see the [contributors](https://github.com/aimacode/aima-swiftthon/graphs/contributors) who are doing a great job of actively improving the project. Many thanks to all contributors, especially @darius, @SnShine, and @reachtarunhere.