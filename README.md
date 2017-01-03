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
