# Optional-Lab-ML-Specialisation-by-Andrew-Ng
- You can download the optional labs for the course Machine Learning Specialisation by Andrew Ng and run it on your pc.
- Create virtual environment of python version `3.7.6` for each course.
- Follow the `Instructions.md` file in each course.

## Setting up conda virtual environment of python version 3.7.6
- For each course create a virtual environment by following the steps
1. **Add the conda-forge Channel:** This channel often has a wider range of package versions available, including older versions of Python.
```
conda config --add channels conda-forge
```
2. **Search for Available Python Versions:** Before creating the environment, you can search for available versions of Python in your configured channels to ensure the version you want is available.
```
conda search python
```
3. **Create the Environment with the Specific Python Version:** Once you have confirmed the availability of the desired Python version, you can create a new Conda environment with that version.
```
conda create --name my_env_name python=3.7.6
```
