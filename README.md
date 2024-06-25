# $\mathrm{CO_2}$-Equilibrium

This repository is designed to be a customizable set of resources to facilitate the understanding of the inorganic chemistry of carbon in water.

An introduction to scientific Python programming using Google Colab along with the Numpy, Matplotlib, and Pandas libraries.[Python Introductory Activity](https://colab.research.google.com/github/wphall/CO2-Equilibrium/blob/main/Python_Introductory_Activity_KEY.ipynb)

An introduction to solving equilibrium problems using mass balance, charge balance, and non-linear least squares. [Solving Equilibrium Problems Using Python.ipynb](https://colab.research.google.com/github/wphall/CO2-Equilibrium/blob/main/Solving_Equilibrium_Problems_Using_Python.ipynb)

[A student notebook divided into seven parts](https://colab.research.google.com/github/wphall/CO2-Equilibrium/blob/main/Student_Notebook_CO2_Equilibrium.ipynb#scrollTo=DQFCCLpto973)
* Parts I to III: a closed system starting with only $\mathrm{CO_2}$ and $\mathrm{H_2O}$ is described and defined in Python. The equilibrium concentrations of atmospheric $\mathrm{CO_2}$ and the aquesous species $\mathrm{[CO_2], [HCO_3^-], [CO_3^{2-}], [H_3O^+]}$, and $\mathrm{[OH^-]}$ are caluculated.  In this portion of the student notebook, many of the code segments are left blank and are intended to be filled in by the students as they work through the caluclations.

    * An optional introduction to looping in Python, storing large datasets as a Pandas dataframe, and plotting using Matplotlib with annotation and labeling. [Handling Data with Pandas and Matplotlib.ipynb](https://colab.research.google.com/github/wphall/CO2-Equilibrium/blob/main/Handling_Data_with_Pandas_and_Matplotlib.ipynb)

* Part IV is a study of the effect of atmospheric CO2 on the pH of rainwater.  At the end of this sections the students will have made a plot of pH as a function of partial pressure of atmospheric $\mathrm{CO_2}$ and compared their experimental results with theory.  Some instructors may choose to stop here.

* Parts V and VI build on the previous sections by considering first the solid $\mathrm{CaCO_3}$ only system (Part V) and then combining the carbon inputs of both atmospheric $\mathrm{CO_2}$ and solid calcium carbonate (Part VI).  This mixed system is complex and other Python functions for constarained non-linear least squares fitting are introduced.

* Part VII takes into account the effects of temerature and ionic strength.  Due to the complexity of these calculations, a larger amount of the code is provided.  By the end of the notebook, students will constuct a model for understanding the effect of atmospheric $\mathrm{CO_2}$ on the pH of oceans that are saturated with limestone.

