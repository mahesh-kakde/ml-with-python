### Environment setup using Anaconda (Windows)
1. Install *[Anaconda Navigator](https://www.anaconda.com/download)*.
2. Open *Anaconda Prompt*.
3. Create a conda environment:
```
conda create -n <env_name> python=<py_version>
```
- Replace `<env_name>` with the desired environment name and `<py_version>` with a compatible Python version.
4. Activate the environment:
```
conda activate <env_name>
```
5. Install the required Python packages:
```
conda install <modules_required>
```
- Use commas to install multiple modules.
6. Navigate to the directory containing the `.ipynb` notebooks:
```
cd <path_to_directory>
```
7. Launch Jupyter Notebook:
```
jupyter notebook
```
- If Jupyter is not installed in the environment:
```
conda install jupyter
```
8. Re-run step 7. The notebooks should open in the browser and be ready to run.

#### Optional
To delete a conda environment:
```
conda remove -n <env_name> --all
```