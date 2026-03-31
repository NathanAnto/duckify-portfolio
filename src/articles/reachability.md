# Reachability

## Analyse

* [Reachability](https://toys-r-us-rex.github.io/Duckify/architecture/robot/reachability_logic.pdf)
* [Reachability - cone search](https://toys-r-us-rex.github.io/Duckify/architecture/robot/reachability_cone_search.pdf)

## Implémentation

* [Fonction `is_reachable`](https://github.com/Toys-R-Us-Rex/ur3e-control/blob/archived/is-reachable/urbasic/URBasic/reachability.py#L206)
* [Fonction `get_reachable`](https://github.com/Toys-R-Us-Rex/ur3e-control/blob/archived/is-reachable-safety/src/safety.py#L79)

[`get_reachable` -> `_cone_search`](https://github.com/Toys-R-Us-Rex/ur3e-control/blob/dev/clean-merge-pipeline/src/safety.py#L357)

## Évaluation

[Démo notebook Get Reachable](https://github.com/Toys-R-Us-Rex/ur3e-control/blob/archived/is-reachable-safety/duckify_simulation/demos/get_reachable_demo.ipynb)

[Plot result](../assets/semaine3/get-reachable-plot.png)