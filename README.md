# AI-reinforcement

### Project link
http://ai.berkeley.edu/reinforcement.html

### how to use multi env on Anaconda
Python 2.7 and 3.9
Use: Anaconda Prompt (anaconda3)

```powershell
conda create -n py27 python=2.7 
activate py27

conda create -n py39 python=3.9
activate py39

you may leave the environment back to your global env by typing
deactivate py27 
or 
deactivate py39
```


```powershell
conda create -n py2 --override-channels -c conda-forge python=2.7 spyder=3.3 qtawesome=0.7
```
```
py2.yaml

name: py2
channels:
  - conda-forge
dependencies:
  - python=2.7
  - spyder=3.3
  - qtawesome=0.7
```

<img width="620" alt="82J0h" src="https://user-images.githubusercontent.com/6225593/166659697-8f8fd14c-274b-494d-aad8-0248d8b7c17c.png">


