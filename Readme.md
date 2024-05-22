# HousingPricePrediction

## Prerequisites
Before installing HousingPricePrediction, ensure that Python is installed on your system. If Python is not installed, you can download it from the [official Python website](https://www.python.org/downloads).

## Installation

1. **Install Miniconda**: If Miniconda is not installed on your system, download and install it from the [Miniconda website](https://docs.conda.io/en/latest/miniconda.html). Follow the installation instructions provided for your operating system.

2. **Create a New Conda Environment**: Before running or installing the package, create a new conda environment using the attached `env.yml` file. You can do this using the following command:

   Here is some Python code:

    ```python
    conda env create -f env.yml

This command will create a new conda environment and install the required packages specified in the `env.yml` file.

3. **Activate the Conda Environment**: After creating the new conda environment, you need to activate it. Activation is essential to ensure that the software in the environment works correctly. You can activate the environment using the following command:
    ```python
    conda activate myenv

3. **Download `housingPricePrediction.whl`**: Download the `housingPricePrediction.whl` file and place it in a folder on your system. Navigate to the directory where `housingPricePrediction.whl` is located using your terminal or command prompt.

4. **Install HousingPricePrediction**: Run the following command in your terminal or command prompt to install HousingPricePrediction using pip:

    ```python
    pip install -r housingPricePrediction.whl


This command will install the required dependencies specified in the `housingPricePrediction.whl` file.

## Testing

1. **Create a Test Script**: After the installation, create a Python script to test the functionality of the installed package. Here's an example Python script (`test_housing_price_prediction.py`) that imports the installed package and runs sample functions or tests to verify its functionality(file attached):


      ```python
       import housingPricePrediction

Run sample functions or tests to verify the package functionality


2. **Run the Test Script**: Save the script and run it using the following command in your terminal or command prompt:

      ```python
       python test_housing_price_prediction.py


Running this script will test the functionality of the installed package.

If there any issue with the package testing contact the developer for support
