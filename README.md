# Parameter-Shift Rule using Qiskit

---

The paper we followed is written by [Gavin E. Crooks : Gradients of parameterized quantum gates using the parameter-shift rule and gate decomposition](https://arxiv.org/abs/1905.13311)

## Prerequisities

See `requirement.txt` or
```bash
pip install -r requirements.txt
```

## Run code

The main code is written in `simulation.ipynb` and the result will be saved in `result_npy`. Data with 128 and 1024 shots have already be saved. To load the trained parameters and record from *npy* files, try

```python
np.load('some_file.npy', allow_pickle=True)
```

Note that it is important to use ```allow_pickle=True``` since we're going to load a ```dict``` file.

To get the plot of the result, see `plot_result.ipynb`