# Nexus Fusion and Forge Integration

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
