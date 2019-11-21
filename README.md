# Build the conda environment
We'll be using Python and some packages for this workshop.
- Check if you have `conda` by running `$conda --version` on your command line interface (e.g. Terminal, cmd, etc..)
- Install Anaconda for your OS if you don't have it at https://www.anaconda.com/distribution/. If you were at our previous workshop, you most likely have it.
- Clone this repo:
```
$ git clone https://github.com/devcNewYork/time-series-prediction.git
```

- Change to the directory:

```
$ cd time-series-prediction
```
 
- Then build the environment with:

```
$ conda env create -f environment.yml
```

- That's it!

And if (for some reason) you need a specific version of any of the packages, update the environment.yml file and run:

```
$ conda env update --prefix ./env --file environment.yml  --prune
```

