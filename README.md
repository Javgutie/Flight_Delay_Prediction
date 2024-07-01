# Flight Delay Predictor

Flight delays not only frustrate air passengers and disrupt their itineraries but also lead to:

-   Reduced efficiency.
-   Increased capital costs due to the reallocation of flight crews and aircraft.
-   Additional crew expenses.

Consequently, an airline's history of flight delays can adversely affect passenger demand.

This repository presents the development of a machine learning-based model for predicting flight delays:

-   Analyzing and extracting insights from the Tunisian airline delay dataset.
-   Developing several machine learning models for predicting flight delays.

The goal is to provide airline stakeholders with an analysis and prediction tool that enables them to make data-driven decisions on preventive measures to avoid flight delays.

The projects consists of three notebooks, which are self-explained by their names.

## Set up your Environment


### **`macOS`** type the following commands : 

- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
    
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:
    ```Bash
    python.exe -m pip install --upgrade pip
    ```
   
The dataset (Flight Delay Prediction Challenge) used in this notebook is saved in a `.zip` file as `data.zip`. To unzip it, copy the block below into your terminal:

```Bash
unzip data.zip
```

More detailed information of the dataset [here](https://zindi.africa/competitions/flight-delay-prediction-challenge).


