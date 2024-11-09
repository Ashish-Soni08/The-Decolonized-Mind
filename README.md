# NVIDIA and LlamaIndex Developer Contest

[NVIDIA](https://developer.nvidia.com/llamaindex-developer-contest)

## THE DECOLONIZED MIND

![The_Decolonized_Mind](/images/decolonized_mind.png)

## Technical Implementation Details

![GPT-4-32K](/images/model_info.PNG)

### Architecture

![Architecture](/images/architecture.jpg)

### Environment Setup

```bash
python -V
# Output -> Python 3.12.1
```

```bash
# create a virtual environment 
python -m venv nim-ai
```

```bash
# activate the virtual enivironment
source nim-ai/bin/activate
```

```bash
# create a Jupyter Notebook kernel
pip install jupyter ipykernel
```

```bash
# add the virtual environment as a kernel for the jupyter notebook
python -m ipykernel install --user --name=nim-ai --display-name="Py3.12-nim-ai"
```

```bash
# verify kernel installation
jupyter kernelspec list
```
