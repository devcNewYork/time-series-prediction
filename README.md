# Build the conda environment
- Install Anaconda for your environment. It'll most likely come with conda
- Then build the environment with:
```
$ conda env create -f environment.yml
```

And if (for some reason) you need a specific version of any of the packages, update the environment.yml file and run:

```
$ conda env update --prefix ./env --file environment.yml  --prune
```

