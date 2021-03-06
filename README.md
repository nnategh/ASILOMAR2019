# Analyzing the Computational Complexity of a Dynamic Model of the Time-varying Spatiotemporal Sensitivity of Neurons in the Visual Cortex

In order to precisely track the dynamics of visual information encoding during saccadic eye movements, we have recently developed a computational model applicable to the sparse, limited neural data available during the short timescale of saccades [[1](#references)]. The time-varying stimulus kernels estimated by the model can provide a precise description of the neurons’ dynamic spatiotemporal sensitivity with high precision during a saccade. Achieving this precision however requires handling a trade-off between the computational complexity, generalizability, and prediction accuracy of the encoding model. In this paper, we derive a principled strategy for the model parameterization to handle this trade-off, which is particularly critical for estimating the high-dimensional models using sparse neuronal data. The results of this analysis can guide optimizing various dimensionality reduction and model parameterization approaches used for the estimation of the generalized linear model-based frameworks applied on spiking data beyond the data and approaches used in this study.

## Data flow
> To see more details about the `dimensionality reduction` method, please click on this [link](METHODS.md). To see the previous version of the model, please click on this [link](https://github.com/nnategh/SVGLM).

[![Data flow](assets/figures/data-flow.svg "Data flow")](METHODS.md)

## References
[1] Niknam, K., Akbarian, A., Clark, K., Zamani, Y., Noudoost, B., & Nategh, N. (2019). Characterizing and dissociating multiple time-varying modulatory computations influencing neuronal activity. PLoS computational biology, 15(9), e1007275. [[HTML] from plos.org](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007275)
