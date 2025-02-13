# THE DECOLONIZED MIND

![The_Decolonized_Mind](images/decolonized_mind.png)

## Technical Implementation Details

### Architecture


### Environment Setup

```bash
python -V
# Output -> Python 3.12.1
```

```bash
# create a virtual environment 
python -m venv langflow-ai
```

```bash
# activate the virtual enivironment
source langflow-ai/bin/activate
```

```bash
# create a Jupyter Notebook kernel
pip install jupyter ipykernel
```

```bash
# add the virtual environment as a kernel for the jupyter notebook
python -m ipykernel install --user --name=langflow-ai --display-name="Py3.12-langflow-ai"
```

```bash
# verify kernel installation
jupyter kernelspec list
```
