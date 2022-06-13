In this exercise, you can study the impact of input parameters of the MO-TRNG on the output entropy rate.

You can launch the application and observe how the number of oscillators, the jitter variance and the accumulation time affect  Shannon entropy and min-entropy rate at the MO-TRNG output.

Your goal is to find the smallest $D$ for which the generator will produce random bits with a Shannon entropy rate higher than 0.997.

You should repeat the procedure for all possible $\frac{\sigma_{tot}}{T_{1}}$ and $N$ values.


## How to launch the exercise ?
* We can execute this exercise on [Colab](https://colab.research.google.com/github/patrickhaddadteaching/TRNG_ex3/blob/main/TRNG_ex3_nb.ipynb)
    * Then press Ctrl+F9 or click on Runtime/Run All
* The exercise is a jupyter notebook compatible with voila.
The following libraries are required:
    * numpy
    * h5py
    * matplotlib
## Examples of procedures to execute the exercise with different systems.
1. Windows
    * First of all, Let clone this repositorie
    ```
     git clone https://github.com/patrickhaddadteaching/TRNG_ex3
    ```
    * [Download and install the latest Miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links).
    * Open the Anaconda Powershell Prompt associated to Miniconda3 and type the following commands to install  to install all the dependencies required by this exercise.
     ```
        conda install jupyter
        conda install numpy
        conda install h5py
        conda install matplotlib
        conda install -c conda-forge voila    
    ```
    * Now, you can either launch the notebook by executing the folowing command in the directory where you cloned this repositorie.
    ```
    jupyter-notebook.exe .\TRNG_ex3_nb.ipynb
    
    ```
    
    * Or, you can directly launch it with voila  by executing the folowing command in the directory where you cloned this repositorie.
    ```
    voila.exe .\TRNG_ex3_nb.ipynb
    ```
2. Linux
3. Mac OS X
