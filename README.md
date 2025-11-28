# Libraries


Installation of the environment:
``` bash
uv venv zuko_tester_env
```

### Activate it

``` bash
source zuko_tester_env/bin/activate
```

### Install scientific + Jupyter stack

``` bash
uv pip install numpy scipy pandas matplotlib seaborn tqdm scikit-learn jupyterlab ipykernel
```

### Install PyTorch and Zuko
``` bash
uv pip install torch torchvision torchaudio zuko
```
