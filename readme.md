# Notebooks for visualizing parameter and state estimation using a NPZD ocean biological model

Five notebooks are currently available:

 * For a brief introduction to the NPZD model see [this notebook](npzd.ipynb).
 * The [EnKF parameter estimation notebook](parameter_estimation_enkf.ipynb) is the most developed, it allows the user to change the parameter estimation setup, the observations, or the EnKF configuration. It further contains a few preconfigured scenarios that highlight parameter optimization-related issues such as parameter interdependence or underdetermined parameters.
 * The [EnKF state estimation notebook](state_estimation_enkf.ipynb) focuses on state estimation but is otherwise very similar to the EnKF parameter estimation notebook. CIt contains no predefined scenarios.
 * The [evolutionary algorithm parameter estimation notebook](parameter_estimation_de.ipynb) introduces a different parameter estimation technique. It is based on a differential evolution evolutionary algorithm.
 * The [MATLAB version](state_estimation_enkf_matlab.ipynb) of the state estimation notebookis a prototype copy of an earlier Python version and may be updated once development is complete.

# Running the notebooks online

Instead of cloning this repository or downloading the code, the notebooks can be run online using [binder](https://mybinder.org/).
Just follow this [link](https://mybinder.org/v2/gh/jpmattern/obm-primer/HEAD).

# Feedback

Feel free use GitHub's issues feature (link above) to provide feedback.

