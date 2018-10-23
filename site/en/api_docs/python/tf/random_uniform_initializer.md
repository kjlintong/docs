

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.random_uniform_initializer

### `class tf.contrib.keras.initializers.RandomUniform`
### `class tf.random_uniform_initializer`



Defined in [`tensorflow/python/ops/init_ops.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.2/tensorflow/python/ops/init_ops.py).

See the guide: [Variables > Sharing Variables](../../../api_guides/python/state_ops#Sharing_Variables)

Initializer that generates tensors with a uniform distribution.

#### Args:

* <b>`minval`</b>: A python scalar or a scalar tensor. Lower bound of the range
    of random values to generate.
* <b>`maxval`</b>: A python scalar or a scalar tensor. Upper bound of the range
    of random values to generate.  Defaults to 1 for float types.
* <b>`seed`</b>: A Python integer. Used to create random seeds. See
    [`tf.set_random_seed`](../tf/set_random_seed)
    for behavior.
* <b>`dtype`</b>: The data type.

## Methods

<h3 id="__init__"><code>__init__</code></h3>

``` python
__init__(
    minval=0,
    maxval=None,
    seed=None,
    dtype=tf.float32
)
```



<h3 id="__call__"><code>__call__</code></h3>

``` python
__call__(
    shape,
    dtype=None,
    partition_info=None
)
```



<h3 id="from_config"><code>from_config</code></h3>

``` python
from_config(
    cls,
    config
)
```

Instantiates an initializer from a configuration dictionary.

Example:

```
initializer = RandomUniform(-1, 1)
config = initializer.get_config()
initializer = RandomUniform.from_config(config)
```

#### Arguments:

* <b>`config`</b>: A Python dictionary.
    It will typically be the output of `get_config`.


#### Returns:

  An Initializer instance.

<h3 id="get_config"><code>get_config</code></h3>

``` python
get_config()
```




