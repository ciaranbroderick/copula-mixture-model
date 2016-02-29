Recent Updates:
1. Added option for analytical gradient computation for speeding up large dimensional problems.
2. Added option for parallelizable gradient computation.
3. Added option for empirical (rank based) marginal CDF estimation

The project creates a gmcdistribution (Gaussian Mixture Copula distribution) class similar to the gmdistribution (Gaussian Mixture distribution) class of the Matlab's stats toolbox. This class is intended for the characterization of multimodal datasets with non-Gaussian modes. Currently it implements the following methods:
1. fit (for fitting the distribution)
2. cluster (for clustering the datapoints given the learnt model).
3. random (for randomly sampling from the model)
4. pdf
5. cdf

Please refer to the following paper for details:

'Parameteric Characterization of Multimodal Distribution with Non-Gassian Modes' A. Tewari et al. to be presented at OEDM workshop in ICDM 2011 (paper included in the package)

The author can be contacted by email tewari.psu@gmail.com for any question/comment/suggestion for improvement.