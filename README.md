# Exercises

Hands-on exercises for working with spectral parameterization.

## Overview

This repository contains hands-on exercises for learning and working with
spectral parameterization (['specparam'](github.com/fooof-tools/)).

Note that these materials are _not_ the official tutorials for specparam, which are
available on the [docsite](https://specparam-tools.github.io/).
Those tutorial materials contain detailed descriptions of the module and functionality,
and can be downloaded as executable notebooks to work with.

These materials are a set of _exercises_, designed to supplement the documentation materials
by offering a set of notebooks that can be worked through, asking the user to write code
to explore and practice the use of spectral parameterization.

## Requirements

This set of exercises requires the Python programming language (version >= 3.7).

These exercises have the following dependencies:

- [specparam](https://github.com/fooof-tools/fooof)
- [neurodsp](https://github.com/neurodsp-tools/neurodsp)

### Installation

If you already have a Python install with an environment you'd like to use,
you just need to install the dependencies, which can be done with `pip`.

```
# Install
pip install specparam, neurodsp
```

If you want to create a new environment for working with these exercises,
you can do so with a tool such as
[conda](https://docs.conda.io/projects/conda/en/stable/index.html).

For example, the following creates and initializes a new conda environment to run the exercises:

```
# Create a new Python environment with conda
conda create --name exercises python=3.12 anaconda

# Activate the new environment
`conda activate exercises`

# Install the remaining required packages
pip install specparam, neurodsp
```

## Additional Materials

These exercises are focused on being hands-on exercises to practice _working with_ spectral parameterization.
For more information on _learning about_ spectral parameterization and related topics, the following additional
resources may be useful.

Documentation for the  materials:
- [specparam documentation](https://fooof-tools.github.io/)
- [neurodsp documentation](https://neurodsp-tools.github.io/)

Additional resources, including open-source projects & visualizers:

- [signal visualizers](https://timeserieszoo.github.io/)
- [oscillation methods project](https://oscillationmethods.github.io)
- [aperiodic methods project](https://aperiodicmethods.github.io)

## References

This tutorial was created and is maintained by
[Tom Donoghue](https://tomdonoghue.github.io/).
