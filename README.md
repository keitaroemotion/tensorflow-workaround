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
