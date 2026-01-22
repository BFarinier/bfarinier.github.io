# Arrays Made Simpler: An Efficient, Scalable and Thorough Preprocessing

Benjamin Farinier, Robin David, Sébastien Bardin, and Matthieu Lemerre

The theory of arrays has a central place in software verification due to its
ability to model memory or data structures. Yet, this theory is known to be hard
to solve in both theory and practice, especially in the case of very long
formulas coming from unrolling-based verification methods. Standard
simplification techniques à la read-over-write suffer from two main drawbacks:
they do not scale on very long sequences of stores, and they miss many
simplification opportunities because of a too crude syntactic (dis-)equality
reasoning.

We propose a new approach to array constraint simplification based on a new
dedicated data structure together with original simplifications and low-cost
reasoning. The technique is efficient, scalable and it yields significant
simplification. The impact on formula resolution is always positive, and it can
be dramatic on some specific classes of problems, e.g. very long formula or
binary-level symbolic execution. While currently implemented as a preprocessing
step, the approach would benefit from a deeper integration inside a dedicated
array solver.

[ [final.pdf](https://easychair.org/publications/open/lSLN)
| [binsec.tar.gz](https://github.com/binsec/binsec/archive/lpar.zip)
| [bench.tar.gz](http://storage.farinier.org/lpar2018/bench.tar.gz)
]
