# Glassnode - BI/Analytics Lead interview exercise

This was an exercise proposed by Glassnode during the interview process for a position as BI/Analytics Lead with them.

# Task

More info about the task can be found at the email received from Glassnode [here](files/bi_lead_challenge.pdf).

# Assumptions/Methodology
- working on a Mac or linux
- running Jupyter Notebook [inside Visual Studio](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) to facilitate generating a report
- using [plotly](https://plotly.com/) for creating the graphs, because I like the feature that allows you to hove over the graph and see some metadata
- loaded the data into a Redshift instance via S3 so I could run SQL

# Setup

Make sure you're at the right place and create a new python environment using `venv`:
```
cd /<project-path>/balena_task
python3 -m venv .venv
```

Activate the virtual environment you just created and install the necessary libraries:
```
source .venv/bin/activate
pip install -r requirements.txt
```

In case you want to host a local Jupyter Notebook instance, just execute `jupyter notebook` and the web app will be available at http://localhost:8888/tree (more details [here](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)).

Alternatively, if you're working on Visual Code, you can simply create a new Notebook by running the **Jupyter: Create Blank New Jupyter Notebook** command from the Command Palette (⇧⌘P) and select the venv you just created as the kernel (more details [here](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)).

The jupyter notebook file can be found [here](glassnode-challenge-solution.ipynb)

# Outcome

The report with the whole analysis, graphs and code can be found [here](glassnode-challenge-solution.html) as an html file (just download it and open in any web browser) and the jupyter notebook file can be found [here](glassnode-challenge-solution.ipynb) in case you want to execute the code yourself.
