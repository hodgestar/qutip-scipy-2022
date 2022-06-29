# SciPy 2022 Tutorial: Exploring open quantum systems with QuTiP

Presenter:
- **Simon Cross**

Institutions:
- **[RIKEN](https://www.riken.jp/en/)**,
  **[Theoretical Quantum Physics Laboratory](https://dml.riken.jp/)**
- **[QuTiP](https://qutip.org)**

## Hello!

If you're attending the SciPy 2022 tutorial named
*Exploring open quantum systems with QuTiP*, and are looking for the
instructions, you have found them.

To get set up you'll need to do the following:

1. Obtain a copy of the contents of this GitHub repository.

2. Install the required Python packages by following the instruction in one of
   the options below.

3. Check that everything is working by running the `pre-tutorial-test.ipynb`
   Jupyter notebook.

4. If this is your very first encounter with quantum mechanics, I have
   recommended some videos to watch before you arrive at the tutorial, just
   so that not everything is completely new to you on the day.

There are instructions for what to do if you get stuck further down.

Don't panic, have fun and see you at the tutorial!


## Download the repository

If you're familiar with GitHub, just clone this repository.

Otherwise, you can download the latest contents of the repository
[here](https://github.com/hodgestar/qutip-scipy-2022/archive/refs/heads/main.zip).


## Installing locally with pip

1. If you don't have Python 3.9 or later installed, install it however
   you usually do. If you are completely new to Python, follow the
   [Getting Started](https://www.python.org/about/gettingstarted/) guide.

2. If you don't have `pip` and `virtualenv` installed, install them by
   following the [instructions](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/). Once you've made it passed these
   first two steps, the hardest part is done.

3. Create a virtual environment by running
   `python3 -m venv -m qutip-tutorial-env`.

4. Activate the environment you have just created by running
   `source qutip-tutorial-env/bin/activate` (on Linux or Mac OS) or
   `.\qutip-tutorial-env\Scripts\activate` (on Windows).

5. Install QuTiP and the other required libraries by running
   `pip install -r requirements.txt`.

6. Open the Jupyter notebook by running `jupyer notebook`.


## Installing locally with conda

1. Install miniconda by following the [instructions](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). This is the hardest step.

2. Create a conda environment named `qutip-tutorial-env` by running
   `conda env create --file environment.yml`.

3. Activate the environment you have just created by running
   `conda activate qutip-tutorial-env`.

4. Open the Jupyter notebook by running `jupyter notebook`.


## Running remotely with Binder

I'd highly recommend installing and running Python locally for the tutorial,
but if that really isn't possible, you are welcome to try running Jupyter
and the necessary dependencies online using either Binder, by clicking the
button below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hodgestar/qutip-scipy-2022/main)

Or by using [Google Colab](https://colab.research.google.com/github/hodgestar/qutip-scipy-2022/blob/main/).

If you are using Google Colab, you'll need to first install QuTiP by running
the command `!pip install 'qutip[full]'` in a cell by itself.


## Testing your installation

Once you have the dependencies installed and Jupyter notebook open, you should
open the notebook named `pre-tutorial-test.ipynb` and run it.

The notebook tests the basic plotting and QuTiP features we will need for the
tutorial and contains instructions for how to tell if it ran correctly.

If the test notebook ran correctly, you're ready for the tutorial!


## What you need for the tutorial

This repository contains everything you need for the tutorial.

It's possible it will be updated between now and mid-July, so please check back
a few days before the tutorial to see if there is anything new.


## What to do if you're new to quantum mechanics

Remain calm! Everything is going to be okay.

To prepare for the tutorial if you've never done any quantum mechanics
before, I recommend that you watch the first six YouTube videos from
a series called
[Quantum computing for the determined](https://www.youtube.com/playlist?list=PL1826E60FD05B44E4)
by Michael Nielsen. It'll mean fewer new concepts to grapple with on the
day, and will allow you gain more from tutorial itself.

Nielsen wrote *the*
[standard textbook on quantum computation](https://en.wikipedia.org/wiki/Quantum_Computation_and_Quantum_Information)
with Isaac Chuang. He presents everything slowly and clearly, and in a
very down to earth way.

The first six videos are:

* [The qubit](https://youtu.be/X2q1PuI2RFI)
* [Tips for working with qubits](https://youtu.be/Jo-RZ27o3Uw)
* [Our first quantum gate: the quantum NOT gate](https://youtu.be/JDDSjsQLv80)
* [The Hadamard gate](https://youtu.be/x6gOp_o7Bi8)
* [Measuring a qubit](https://youtu.be/SMbh0GgCN7I)
* [General single-qubit gates](https://youtu.be/SWKuH9emuag)

Don't be afraid to watch a video multiple times if you need to. They're not
particularly long, and sometimes just taking a break and going through the
material a second time really helps.

You're welcome to watch the rest of the series if you like too. Our tutorial
focuses much more on simulating real atoms, and so it heads in a different
direction to Nielsen's series.

If you'd like to brush up on vectors and matrices, Nielsen recommends looking
at the
[Khan Academy, Linear Algebra](https://www.khanacademy.org/math/linear-algebra)
videos, and I second the recommendation.

If you encounter any questions while going through the videos, you're welcome
to ask me via the conference channels (see below) or bring them with you to
the tutorial.


## What to do if you're NOT new to quantum mechanics

You're probably all set for what you need to know, and ready to diagonalise
some Hamiltonians, solve Schrödinger's equation, find out what a Liouvillian
is, and explore QuTiP!


## What to do if you're stuck

If you're having trouble setting up your environment for the tutorial, you're
welcome to create an issue in this repository
[here](https://github.com/hodgestar/qutip-scipy-2022/issues/new) and I'll do my
best to help.

If you're looking for help with QuTiP, you can message the
[QuTiP Google Group](https://groups.google.com/g/qutip), and I or someone
else will reply there.

If you'd like to contact me directly, you can do so via the conference
channels. I'm not sure what the conference channels are yet, but in the
past there was a SciPy conference Slack channel. I'll add the details here
once I have them.
