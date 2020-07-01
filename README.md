# cuahsi-stacks at Waterhackweek

This is a compilation of docker images that follow the SPEC pattern.

Use the hydrolearn-dev branch to test and merge new updates.

Typical workflow: 
Use the JupyterHub kernel.  Install an additional library or update. 
Then the conda environment, run this code to make an updated file: 

`pip freeze > requirements-modulename-modnum-.txt`

Add this updated file to the HydroLearn developer branch. 

