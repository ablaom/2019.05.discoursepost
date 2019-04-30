# MLJ - Machine Learning in Julia

![](https://github.com/alan-turing-institute/MLJ.jl/blob/master/docs/src/learningcurves.png) | ![](https://github.com/alan-turing-institute/MLJ.jl/blob/master/docs/src/heatmap.png)
------------------------|--------------------------
![](https://github.com/alan-turing-institute/MLJ.jl/blob/master/docs/src/two_model_stack.png)  | ![](https://github.com/alan-turing-institute/MLJ.jl/blob/master/docs/src/MLPackages.png)


[MLJ](https://github.com/alan-turing-institute/MLJ.jl) is a new
flexible framework for composing and tuning supervised and
unsupervised learning models, currently scattered in assorted Julia
packages, as well as wrapped models from other languages. 

The package has been developed primarily at [The Alan Turing
Institute](https://turing.ac.uk) but enjoys a growing list of advisors
and
[contributors](https://github.com/alan-turing-institute/MLJ.jl/blob/master/CONTRIBUTE.md). If you like the project, please star the GitHub [repo](https://github.com/alan-turing-institute/MLJ.jl) to boost the prospects of a **pending funding review.**  


### Quick links

&#9758; [MLJ vs ScikitLearn.jl](https://alan-turing-institute.github.io/MLJ.jl/dev/frequently_asked_questions/)  

&#9758; Video from [London Julia User Group meetup in March 2019](https://www.youtube.com/watch?v=CfHkjNmj1eE) (skip to [demo at 21'39](https://youtu.be/CfHkjNmj1eE?t=21m39s)) &nbsp; 

&#9758; [Basic Usage](https://alan-turing-institute.github.io/MLJ.jl/dev/) and
[Tour](https://github.com/alan-turing-institute/MLJ.jl/blob/master/docs/src/tour.ipynb)


&#9758; Building a [self-tuning random
  forest](https://github.com/alan-turing-institute/MLJ.jl/blob/master/examples/random_forest.ipynb)

&#9758; An MLJ [docker image](https://github.com/ysimillides/mlj-docker) (including tour)

&#9758; Implementing the MLJ interface for a [new model](https://alan-turing-institute.github.io/MLJ.jl/dev/adding_models_for_general_use/) 
&nbsp; 

&#9758; How to [contribute](https://github.com/alan-turing-institute/MLJ.jl/blob/master/CONTRIBUTE.md)

&#9758; Julia [Slack](http://julialang.slack.com) channel: \#mlj.

<!---
![](wrapped_ridge.png)
-->


### Key implemented features

- **Learning networks.** Flexible model composition beyond traditional
  pipelines (more on this below).

- **Automatic tuning.** Automated tuning of hyperparameters, including
  composite models. Tuning implemented as a model wrapper for
  composition with other meta-algorithms.
  
- **Homogeneous model ensembling.**

- **Registry for model metadata.** Metadata available without loading
  model code. Basis of a "task" interface and facilitates
  model composition.
  
- **Task interface.** Automatically match models to specified learning
  tasks, to streamline benchmarking and model selection.
  
- **Clean probabilistic API.** Improves support for Bayesian
  statistics and probabilistic graphical models.
  
- **Data container agnostic.** Present and manipulate data in your
  favorite Tables.jl format.

- **Universal adoption of categorical data types.** Enables model
  implementations to properly account for classes seen in training but
  not in evaluation.

Enhancements planned for the near future include integration of
Flux.jl **deep learning** models, and **gradient descent tuning** of
continuous hyperparameters using automatic differentiation.

Feedback very welcome!


