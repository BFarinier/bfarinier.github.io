# Not All Bugs Are Created Equal, <br />But Robust Reachability Can Tell The Difference

Guillaume Girol, Benjamin Farinier, and Sébastien Bardin

This paper introduces a new property called robust reachability which refines
the standard notion of reachability in order to take replicability into
account. A bug is robustly reachable if a controlled input can make it so the
bug is reached whatever the value of uncontrolled input. Robust reachability is
better suited than standard reachability in many realistic situations related
to security (e.g., criticality assessment or bug prioritization) or software
engineering (e.g., replicable test suites and flakiness).

We propose a formal treatment of the concept, and we revisit existing symbolic
bug finding methods through this new lens. Remarkably, robust reachability
allows differentiating bounded model checking from symbolic execution while
they have the same deductive power in the standard case. Finally, we propose
the first symbolic verifier dedicated to robust reachability: we use it for
criticality assessment of 4 existing vulnerabilities, and compare it with
standard symbolic execution.

[ [final.pdf](https://link.springer.com/content/pdf/10.1007/978-3-030-81685-8_32.pdf)
]
