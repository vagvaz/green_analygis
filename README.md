# A jupyter notebook to analyze Geo data

this is a work in progress to analyze geographical data
regarding plant diseases and plants. right now only the visualization works.
The app does not need internet connection, one need to have downloaded into files and load and
visualize them.

# Installation

- Install python >=3.12

- Go into the project directory

- Create a virtual environment for python (Optional) 
```python -m venv gis_venv```

- Activate the virtual environment if you created
```
Bash: source gis_venv/bin/activate
Windows: gis_venv/bin/Activate.ps1
```

- Update pip
```python -m pip install --upgrade pip```

- Install requirements
```python -m pip install -r requirements.txt```

- For jupyter notebook run 
```jupyter lab```
this will open a browser with the jupyter notebook address localhost:8000

- For a web-app interface run,
```voila green_analygis.ipynb```

this will open the browser to localhost:8866 with a web-app, right now only the visualization works.


