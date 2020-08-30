# XAI_workshop_ODSC2020

This repository contains the materials for my session 'Explainable ML: Application of different approaches' at the ODSC, Europe conference of September 2020.


Have a look at the **requirements.txt** to see versions of which packages you may need in order to replicate the code. 

You may find it better to work in a virtual environment and install the packages there, instead of potentially distrupting other existing versions you may have of some of these packages. You may choose to work with a *pip virtualenv*, *conda* or to avoid the Shell, you can set it up directly in Anaconda navigator. 

The powerpoint document contains the slides, which give a definition of explainability and arguments for(and against) it. It also presents a taxonomy of XAI approaches, and contains short technical introductions of the methods applied.

Finally, the jupyter notebook file, *XAI_dibates_df.ipynb* contains a detailed walk through of a few explainability approaches, using the classical scikit-learn diabetes use case. Though a toy problem, it allows us to demonstrate the following approaches:

- RuleFit 
- Partial dependency plots
- Individual conditional expectations
- Global surrogate models
- LIME
- Shap



