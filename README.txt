Master Thesis Code and Results

Name: Farzaneh Behmanesh

Thesis topic:
Physics-Guided and Uncertainty-Aware Surrogate Modeling of Acoustic Wave Resonators Using Artificial Neural Networks

Description:
This folder contains the Google Colab notebooks used for the experiments in my master thesis. 
The notebooks include the Python code and the saved output results, such as printed numerical values, plots, evaluation metrics, and comparison results.

The codes were developed and executed in Google Colab using Python.

------------------------------------------------------------
Folder content
------------------------------------------------------------

1. forwardSurrogateModel.ipynb
   Contains the main forward surrogate-model experiment and the comparison between MLP and CNN architectures.

2. optimizerStudy.ipynb
   Contains the optimizer comparison study, including Adam, SGD, and RMSprop.

3. batchSizeStudy.ipynb
   Contains the batch-size study for the forward surrogate model.

4.networkArchitectureStudy.ipynb
   Contains the comparison of different neural-network architectures.

5. activationFunctionStudy.ipynb
   Contains the activation-function comparison study.

6. augmentationStudy.ipynb
   Contains the data-augmentation experiment.

7. regularizationStudy.ipynb
   Contains the L2-regularization study.

8. learningRateStudy.ipynb
   Contains the learning-rate comparison study.

9. combinedEffectofHyperParameters.ipynb
   Contains the combined hyperparameter study.

10. temperatureDependantModel.ipynb
    Contains the temperature-dependent ECP prediction model.

11.temperatureforAdmittanceMultiResonator.ipynb
    Contains the direct admittance prediction and multi-resonator temperature-dependent experiments.

12. decomposition_CalibrationDensity_TrainingRange.ipynb
    Contains the uncertainty decomposition, calibration, training-density, and temperature-range experiments.

13. uncertaintyPropagation.ipynb
    Contains the uncertainty propagation experiment, where predicted ECP uncertainty is propagated through the MBVD model to obtain uncertainty bands in the admittance response.

14. alarmBehaviorUnderDifferentUncertaintySources.ipynb
    Contains the alarm/reliability analysis under different uncertainty sources.

------------------------------------------------------------
How to run
------------------------------------------------------------

The notebooks can be opened and executed in Google Colab.

Recommended procedure:
1. Open the desired .ipynb file in Google Colab.
2. Run the cells from top to bottom.
3. The results and plots are shown directly inside the notebook.

Some notebooks may take longer to run because they include training of neural networks or repeated experiments.

------------------------------------------------------------
Required Python packages
------------------------------------------------------------

The main required packages are:

numpy
pandas
matplotlib
scipy
scikit-learn
tensorflow
keras

These packages are available by default or can be installed in Google Colab.

------------------------------------------------------------
Notes
------------------------------------------------------------

The notebooks contain the saved outputs used for the thesis results. 
Therefore, even without re-running the full code, the main plots and numerical results can be viewed directly inside the notebooks.

The codes are organized according to the experimental chapters and studies presented in the thesis.