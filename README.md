# Zero
Zero is a *library* for PyTorch users. Zero provides tools that:
- simplify training loop, models evaluation, models application and other typical Deep Learning tasks
- are not tied to any "central entity", i.e. they solve small orthogonal problems and can be used together with PyTorch *frameworks* such as [Ignite](https://pytorch.org/ignite), [Lightning](https://pytorch-lightning.readthedocs.io/en/latest), [Catalyst](https://catalyst-team.github.io/catalyst) and [others](https://pytorch.org/ecosystem)
- do not affect the way you write and organize code

**NOT READY FOR PRODUCTION USAGE.** Zero is tested, but not battle-tested. You can give it a try in non-mission-critical research.

## Overview
- [High-level overview](./other/OVERVIEW.md) (the fastest way to undestand the spirit of Zero)
- [Classifiction example (MNIST)](https://github.com/Yura52/zero/blob/master/examples/mnist.py)

No documentation is currently available, but you can learn Zero from the links above and by reading the source code.

## Installation
**Please, note** that if you don't have PyTorch installed, then the CPU-version will be installed together with Zero. If you want to have the GPU-version of PyTorch, install it **before** installing Zero. See the [PyTorch Get Started](https://pytorch.org/get-started/locally/) for corresponding instructions.

```bash
$ pip install libzero
```

### Dependencies
- Python >= 3.6
- NumPy >= 1.18
- PyTorch >= 1.5 (CPU or CUDA >= 10.1)
- pynvml >= 8.0

There is a chance that Zero works fine with older versions of the mentioned software, however, it is tested only with the versions given above.

## How to contribute
- Take part in the discussions: [GitHub]()
- See issues with the labels ["discussion"](https://github.com/Yura52/zero/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22+label%3Adiscussion) and ["help wanted"](https://github.com/Yura52/zero/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)
- Open issues with bugs, ideas and any other kind of feedback

If your contribution includes pull requests, see [CONTRIBUTING.md](./other/CONTRIBUTING.md).

## Why "Zero"?
There is no correct explanation, just a set of associations:
- Zero aims to be [zero-overhead](https://isocpp.org/wiki/faq/big-picture#zero-overhead-principle) in terms of both mental and technical overhead. It means that solutions, provided by Zero, try to be as minimal, intuitive and easy to learn, as possible.
- Zero is the most mimimalistic and easy-to-use number.
- Zero loss is the unattainable dream we all want to make come true.
