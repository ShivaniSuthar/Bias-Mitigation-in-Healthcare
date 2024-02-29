## Project Summary:

In this project, my team and I used Deloitte's AIF 360 Fairness Toolkit and the Medical Expenditure Panel Survery (MEPS) dataset in order to build and test models to mitigate bias in healthcare expenditure and resource allocation systems. 

We built logistic classification and random forest models and evaluated our models using fairness metrics including best balanced accuracy, disparate impact, average odds difference value, statistical parity difference value, and equal opportunity difference value.

This project was completed using Python in a Jupyter Notebook primarily using pandas, seaborn, sklearn, and aif360 packages

## Installation and Setup

1. **Install Jupyter:** Ensure your installation of Jupyter is up to date. If you haven't installed Jupyter, you can do so via Anaconda or pip. For detailed instructions, visit [Jupyter's installation guide](https://jupyter.org/install).

2. **Virtual Environment (Optional):** It's recommended to set up a virtual environment for your project. This can be done using:

`python -m venv myenv
source myenv/bin/activate # On Windows use myenv\Scripts\activate`

3. **Install Required Packages:** Install the necessary packages using pip:

`pip install matplotlib numpy IPython pandas seaborn sklearn aif360`

4. **Verify Installation:** To ensure everything is installed correctly, try importing the packages in a Python shell or a Jupyter notebook:

`import matplotlib, numpy, IPython, pandas, seaborn, sklearn, aif360`

5. **Troubleshooting:** If you encounter any issues, check for common errors like version conflicts or missing dependencies. The documentation for each package can provide more specific guidance.

Remember to regularly update your packages to get the latest features and bug fixes.

6. **Acquire Data:** Navigate to [the provided URL](https://www.kaggle.com/datasets/nanrahman/mepsdata/) and download the data. Place both .csv files in the same folder as the notebook.

7. **Launch Jupyter:** Run `jupyter-lab` in your command prompt and navigate to and launch the notebook.
