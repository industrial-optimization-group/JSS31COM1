[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/industrial-optimization-group/JSS31COM1/HEAD)

# JSS31COM1

Requirements:

- Python 3.8 or up
- Create a virtual environment using [this guide](https://janakiev.com/blog/jupyter-virtual-envs/).
- The `jupyterlab` python package
- The `desdeo` python package

Troubleshooting:

- When using a virtual environment, you might need to create a custom kernel for
  jupyterlab to use. To do so, you can use the following command: `python -m ipykernel install --user --name nameofkernel`. You can replace `nameofkernel`
  with whatever you want to name your custom kernel. This name will be displayed
  when selecting a kernel in jupyterlab.
- If everything else fails, you can run the notebooks in binder by clicking the _Binder_ badge at the top of this README or by following [this link](https://mybinder.org/v2/gh/industrial-optimization-group/JSS31COM1/HEAD). Note that using binder is significantly slower than running the notebooks locally.
