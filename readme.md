# Notebooks for visualizing parameter and state estimation using a NPZD ocean biological model

Five notebooks are currently available:

 * For a brief introduction to the NPZD model see [this notebook](npzd.ipynb).
 * The [EnKF parameter estimation notebook](parameter_estimation_enkf.ipynb) is the most developed, it allows the user to change the parameter estimation setup, the observations, or the EnKF configuration. It further contains a few preconfigured scenarios that highlight parameter optimization-related issues such as parameter interdependence or underdetermined parameters.
 * The [EnKF state estimation notebook](state_estimation_enkf.ipynb) focuses on state estimation but is otherwise very similar to the EnKF parameter estimation notebook. CIt contains no predefined scenarios.
 * The [evolutionary algorithm parameter estimation notebook](parameter_estimation_de.ipynb) introduces a different parameter estimation technique. It is based on a differential evolution evolutionary algorithm.
 * The [MATLAB version](state_estimation_enkf_matlab.ipynb) of the state estimation notebookis a prototype copy of an earlier Python version and may be updated once development is complete.

## Running the notebooks online

Instead of cloning this repository or downloading the code, the notebooks can be run online using [binder](https://mybinder.org/).
Just follow this [link](https://mybinder.org/v2/gh/jpmattern/obm-primer/HEAD). 

## If you ...

### only have a few minutes

 * Instead of running the notebooks, open up the (static) notebooks on this webpage.
 * Note the shape of the cost function and the strong interdependence between the phytoplankton growth and mortality parameters in the [EnKF parameter estimation notebook](parameter_estimation_enkf.ipynb).

### have 15 minutes
 
 * Run the [notebooks](https://mybinder.org/v2/gh/jpmattern/obm-primer/HEAD) online.
 * Select the EnKF parameter estimation notebook (parameter_estimation_enkf.ipynb), and run a few of the scenarios.

### have 30 minutes

 * Try out one of the other notebooks: the [evolutionary algorithm parameter estimation notebook](parameter_estimation_de.ipynb) if you are more interested in parameter estimation, or the [EnKF state estimation notebook](state_estimation_enkf.ipynb).
 * For state estimation: modify the number of observation and the observed variables and note the effect on the estimation result. 
 * For evolutionary algorithm parameter estimation: remove the pseudo-random number generator seed and run the notebook a few times. The variability in the results explains why this type of algorithm is typically multiple times, often with different initial estimates. Can the variability be reduced by improving the initial parameter estimates?

### make it a project

 * Fork this repository or download the code and run it locally.
 * Modify one of the EnKF notebooks to perform both state and parameter estimation together.

## Feedback

Feel free use GitHub's issues feature (link above) to provide feedback.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
