# LLM Notebooks

A couple of notebooks for introducing local LLM inference and fine tuning.
The notebooks are already executed, so you can see the results via the github interface.

## Running it yourself

Clone the repository:
```bash
git clone https://github.com/RaulPPelaez/llm_handson_pablo_2025
cd llm_handson_pablo_2025
```
Dependencies can be installed via [conda](github.com/conda-forge/miniforge) via the `environment.yml` file:

```bash
conda env create 
```

Open the notebooks in your favorite Jupyter environment, such as [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) or [VSCode](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).

## Hardware requirements

I ran these in a MacBook Pro with an M4 Pro chip and 24GB of RAM.
The LoRA notebook is currently configured to use an Apple silicon processor (MPS backend in torch), but this can be easily changed.
