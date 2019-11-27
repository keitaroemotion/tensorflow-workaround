# Tensorflow workaround

```
$ sudo pip3 install -U virtualenv
$ virtualenv --system-site-packages -p python3 ./venv
$ source ./venv/bin/activate
```

## to get out
```
(venv) deactivate
```

```
(venv) pip install --upgrade tensorflow
(venv) python -c "import tensorflow as tf;print(tf.reduce_sum(tf.random.normal([1000, 1000])))"
```

## key words

- [epoch](https://deepai.org/machine-learning-glossary-and-terms/epoch)
- [epsilon-greedy algorithm](https://jamesmccaffrey.wordpress.com/2017/11/30/the-epsilon-greedy-algorithm/)
- [multi-arm-bandit](https://towardsdatascience.com/solving-multiarmed-bandits-a-comparison-of-epsilon-greedy-and-thompson-sampling-d97167ca9a50)

## other links
- https://matplotlib.org/
