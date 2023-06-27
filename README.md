


```shell
conda env create -f environment.yml
```

```shell
conda activate venv_MoveNet_test1 
```

To update packages
```shell
conda env update --file environment.yml --prun
```
To check packages 
```shell
conda list 
```

to make it show up on our kernel 
```shell
ipython kernel install --user --name=venv_MoveNet
```

restart the kernel if needed 