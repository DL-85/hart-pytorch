HART on PyTorch
===

A minimal (?) reproduction of [HART](https://github.com/akosiorek/hart).

Usage:

Download KTH Dataset first from [here](https://drive.google.com/a/nyu.edu/file/d/1KBQFWWaUg1ePPX2EXietBtGL2kOf-QIU/view?usp=sharing)
and unpack it to the repo directory.
You will have `KTHBoundingBoxInfo.txt` and a directory called `frames` in the
same place as the source code files.

Then run `main.py` with Python 3.

If you want to run with CUDA, set the environment variable `USE_CUDA=1`.

The feature is not complete; TODO:
- [ ] Gradient clipping
- [x] CUDA support
- [x] Validation and Test
- [ ] Visualization (Tensorboard or Visdom; I would like to use Visdom but probably not until they have sliders)
