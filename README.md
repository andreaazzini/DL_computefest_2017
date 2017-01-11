# Deep Learning Workshops
## Computefest 2017

### Requirements

Hi everybody. Welcome to the Computefest 2017 Deep Learning workshops!
You should install the following Python libraries in order to read and run
the code in the notebooks. You can install them using the `pip` package manager,
or any other package manager of your choice.

```
sudo pip install tensorflow jupyter matplotlib
```

#### Windows

It looks like TensorFlow is only supported natively on Python 3.5.
You can set up a Python 3.5 environment with conda as follows:

```
conda create -n tensorflow python=3.5
source activate tensorflow
```

If source activate doesn't work, try with `activate tensorflow`.

After your environment is created, you just need to install tensorflow, jupyter and matplotlib with pip:

```
pip install --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-0.12.1-cp35-cp35m-win_amd64.whl
pip install jupyter matplotlib
```

If you run into a setuptools issue, you can fix it by reinstalling setuptools manually. Download [ez_setup.py](https://bootstrap.pypa.io/ez_setup.py) and run it:

```
python ez_setup.py
```

Now you should be able to install the libraries with pip (`pip install tensorflow jupyter matplotlib`) and finally run jupyter:

```
jupyter notebook
```

### Check everything works fine

Once you've installed the libraries, run `jupyter notebook` from the root of
this project. Open the `Init.ipynb` notebook and run the cells. They will just
import the libraries and, if nothing breaks, it means that you're all set for
the workshops

### Troubleshooting

*OSError: [Errno 1] Operation not permitted*: you can run into this issue
when installing the aforementioned libraries. I suggest you to fix this by
installing the [Homebrew](http://brew.sh/index_it.html) package manager.

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Then, just reinstall Python.

```
brew install python
```

Alright, the installation of the requirements should work now.

```
sudo pip install tensorflow jupyter matplotlib
```
