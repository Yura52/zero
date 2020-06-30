Zero
====

.. __INCLUDE__

Zero is a general-purpose library for PyTorch users. Zero:

- simplifies training loop, models evaluation, models application and other typical Deep
  Learning tasks
- provides a collection of "building blocks" and leaves code organization to you
- can be used on its own or together with PyTorch frameworks such as
  `Ignite <https://github.com/pytorch/ignite>`_,
  `Lightning <https://github.com/PytorchLightning/pytorch-lightning>`_,
  `Catalyst <https://github.com/catalyst-team/catalyst>`_ and
  `others <https://pytorch.org/ecosystem>`_

**NOT READY FOR PRODUCTION USAGE.** Zero is tested, but not battle-tested. You can give
it a try in non-mission-critical research.

Overview
--------

- (coming soon) Website, `Code <https://github.com/Yura52/zero>`_
- (coming soon) Release Announcement
- (coming soon) Learn Zero
- `Classification task example (MNIST) <https://github.com/Yura52/zero/blob/master/examples/mnist.py>`_

Installation
------------

If you plan to use the GPU-version of PyTorch, install it **before** installing Zero
(otherwise, the CPU-version will be installed together with Zero).

.. code-block:: bash

    $ pip install libzero

Dependencies
^^^^^^^^^^^^

- Python >= 3.6
- NumPy >= 1.18
- PyTorch >= 1.5 (CPU or CUDA >= 10.1)
- pynvml >= 8.0

There is a good chance that Zero works fine with older versions of the mentioned
software, however, it is tested only with the versions given above.

How to contribute
-----------------

- See `issues <https://github.com/Yura52/zero/issues>`_, especially with the labels
  `"discussion" <https://github.com/Yura52/zero/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22+label%3Adiscussion>`_
  and `"help wanted" <https://github.com/Yura52/zero/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22>`_
- `Open issues <https://github.com/Yura52/zero/issues/new/choose>`_ with bugs, ideas and
  *any* other kind of feedback

If your contribution includes pull requests, see `CONTRIBUTING.md <https://github.com/Yura52/zero/blob/master/other/CONTRIBUTING.md>`_.

Why "Zero"?
-----------------

Zero aims to be `zero-overhead <https://isocpp.org/wiki/faq/big-picture#zero-overhead-principle>`_ in terms of *mental* overhead:

- with Zero, you learn *tools* (functions, classes, etc.), but you don't learn *patterns*
- solutions, provided by Zero, try to be as minimal, intuitive and easy to learn, as possible