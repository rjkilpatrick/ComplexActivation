# Complex losses

`complex-loss` is a Python package that provides CUDA accelerated loss functions for [PyTorch](https://pytorch.org/).

This library was created in response to <https://github.com/pytorch/pytorch/issues/47052>.

Complex numbers are far richer than the real numbers and as such need their own loss functions.

The project is currently in active development, with the intention of devloping

## Installation

---

### Binaries

These aren't available yet, but hopefully will be migrated to PyPi.

### From Source

If you're installing from source, you need to install PyTorch.

``` bash
git clone https://github.com/rjkilpatrick/complex-loss
python3 ./setup.py
```

## Loss functions Provided

-[ ] `torch.nn.ELU`
-[ ] `torch.nn.Hardshrink`
-[ ] `torch.nn.Hardsigmoid`
-[ ] `torch.nn.Hardtanh`
-[ ] `torch.nn.Hardswish`
-[ ] `torch.nn.LeakyReLU`
-[ ] `torch.nn.LogSigmoid`
-[ ] `torch.nn.MultiheadAttention`
-[ ] `torch.nn.PReLU`
-[ ] `torch.nn.ReLU`
-[ ] `torch.nn.ReLU6`
-[ ] `torch.nn.RReLU`
-[ ] `torch.nn.SELU`
-[ ] `torch.nn.CELU`
-[ ] `torch.nn.GELU`
-[ ] `torch.nn.Sigmoid`
-[ ] `torch.nn.SiLU`
-[ ] `torch.nn.Softplus`
-[ ] `torch.nn.Softshrink`
-[ ] `torch.nn.Softsign`
-[ ] `torch.nn.Tanh`
-[ ] `torch.nn.Tanhshrink`
-[ ] `torch.nn.Threshold`
