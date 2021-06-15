This is a instruction for initializing a conda env for the GR2 code running.  

According to the setup.py, the python version is <=3.6

```angular2html
conda create -n gr2 tensorflow-gpu=1.12.0 pytorch=1.0.0 cudatoolkit=9 python=3.6 -c pytorch -y
```

Some other modifications are made in requirements.txt.

Need to test if the code can be runned without mujoco-py.

rllab and multiagent-particle-envs should be installed automatically by requirements.txt.

