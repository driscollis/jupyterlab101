# Chapter 1

This chapter covers installing and configuring JupyterLab. Following is a brief synopsis. All commands are run in a terminal or command prompt.

## Installing with Python

If you do not have Python installed, go to the Python website: https://www.python.org/downloads/

After installing Python, run the following:

```
python -m pip install jupyterlab
```

or

```
python3 -m pip install jupyterlab
```

## Installing into a Python Virtual Environment

Create the virtual environment:

```
python -m venv MY_VIRTUAL_ENV_NAME
```

Activate it on Mac or Linux:

```
source bin/activate
```

On Windows, the activate command is found in a batch or Powershell file inside the Scripts folder:

```
Scriots/activate
```

Install JupyterLab in the virtual environment:

```
python -m pip install jupyterlab
```

## Installing with Anaconda

If you do not have Anaconda, you can get it here: https://docs.anaconda.com/anaconda/install/

After installing Anaconda, run the following:

```
conda install -c conda-forge jupyterlab
```

