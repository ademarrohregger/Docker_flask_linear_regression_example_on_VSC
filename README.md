# Docker_flask_linear_regression_example_on_VSC
Docker_flask_linear_regression_example_on_VSC

## Reference

+ [LinuxTips video by Natalia Raythz](https://youtu.be/J5E59YgbyYo)
  - [about Natalia](https://github.com/NatOps)
  
+ [Another Linear Regression example](https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols.html#sphx-glr-auto-examples-linear-model-plot-ols-py)

+ [VSC - Developing inside a Container](https://code.visualstudio.com/docs/remote/containers)

+ [Python flask.request.args() Examples](https://www.programcreek.com/python/example/51530/flask.request.args)
  
+ [pickle - Python object serialization](https://docs.python.org/3/library/pickle.html)


## Docker commands after coding (assuming docker desktop is running)

docker build -t  stayhome .

docker images 

docker run -p 1000:80 stayhome


## Local link to access

+ [http://localhost:1000/isAlive](http://localhost:1000/isAlive)

    - Answer must be: 

      - TRUE



+ [http://localhost:1000/prediction/?f=0.04](http://localhost:1000/prediction/?f=0.04)

    - Answer must be: 

      - [ 190.11089458]
      

