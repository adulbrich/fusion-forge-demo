# Nexus Fusion and Forge Integration Demo

This demo illustrates:

- the creation of a Fusion Workflow,
- adding input datasets directly in Fusion,
- initializing the project context with the Forge,
- registering datasets and activities in the Forge,
- linking activities to steps in Fusion.

Todo:

- read the input dataset directly from Fusion

## Happy Path

1. In Nexus Fusion, create a new project in the Workflow app.
2. Create three consecutive steps in your Workflow project: "Step 1. Data Analysis", "Step 2. Build Models", "Step 3. Validate".
3. Add Input Dataset to "Step 1. Data Analysis".
4. Clone this repository.
5. Follow the Nexus Forge setup instructions below.
6. Launch jupyter lab and open the `demo.ipynb` notebook.
7. Configure the Forge with the right organization and project.
8. Run the notebook.
9. In Fusion, link the newly created activities to their corresponding step.
10. ...
11. Success!

## Installing Nexus Forge

### Install conda (optional)

[Installing on macOS](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html)

### Create an environment (optional)

```bash
conda create -yn kgforge python=3.7
```

### Switch to the environment (optional)

```bash
conda activate kgforge
```

### Install the Nexus Forge

```bash
pip install nexusforge
```

### Get Mappers material

```bash
git clone https://bbpcode.epfl.ch/code/dke/kgforge-mappers
```

### Install the Mappers

```bash
pip install ./kgforge-mappers
```

### Install Jupyterlab

```bash
pip install jupyterlab
```

### Launch notebooks

```bash
jupyter lab ./kgforge-mappers/examples/notebooks/
```

## References

The code of the demo was inspired by [Basic Analysis of the Iris Data set Using Python
](https://medium.com/codebagng/basic-analysis-of-the-iris-data-set-using-python-2995618a6342).
