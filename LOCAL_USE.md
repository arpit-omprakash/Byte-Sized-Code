# Running the notebooks on your local machine

Follow the steps outlined below to run the repo in your local machine configured with [Python 3](https://www.python.org/download/releases/3.0/).

1. Create and Activate a Virtual Environment

    This step creates a virtual environment where you can install the necessary python packages to run the notebooks and other associated projects.  
    This step is optional (but we recommend you follow this, or make sure you understand the consequences of not following this step).  
    
    Creating the virtual environment.  
    On macOS and Linux:  
    ```bash
    python3 -m venv env
    ```

    On Windows:  
    ```	
    py -m venv env
    ```

    Activating the virtual environment.  
    On macOS and Linux:
    ```bash
    source env/bin/activate
    ```

    On Windows:
    ```
    .\env\Scripts\activate
    ```

2. Install the Requirements

    This step installs the required packages and dependencies before you can fire up the notebook.  
    Run the following after activating the virtual environment:    
    ```bash
    pip install -r requirements.txt
    ```

3. Boot up Jupyter

    You should have installed Jupyter and other dependencies to run the notebooks after the last step.  
    Start the jupyter notebook server from the CLI.  
    ```bash
    jupyter notebook
    ```

4. Enjoy

    [Here](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html) is a handy guide to working with jupyter notebooks.  
    Feel free to email or contact if there is any other issue. 