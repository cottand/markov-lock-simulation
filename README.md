# Simulation of a M/M/1/k State dependent Markovian Queue

This queue models a lock shared between _n_ cores of a processor, where each loops to execute a piece of individual code, then a critial shared section.

We look at how cache coherency between the cores makes it so that more cores actually makes the system less efficient.

I used a Jupyter notebook with a [Kotlin kernel](https://github.com/Kotlin/kotlin-jupyter), and plotted using [lets-plot](https://github.com/JetBrains/lets-plot-kotlin).

