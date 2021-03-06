### `tf.truncatemod(x, y, name=None)` {#truncatemod}

Returns element-wise remainder of division. This emulates C semantics where

true, this follows C semantics in that the result here is consistent
with a flooring divide. E.g. `floor(x / y) * y + mod(x, y) = x`.

*NOTE*: `Mod` supports broadcasting. More about broadcasting
[here](http://docs.scipy.org/doc/numpy/user/basics.broadcasting.html)

##### Args:


*  <b>`x`</b>: A `Output`. Must be one of the following types: `int32`, `int64`, `float32`, `float64`.
*  <b>`y`</b>: A `Output`. Must have the same type as `x`.
*  <b>`name`</b>: A name for the operation (optional).

##### Returns:

  A `Output`. Has the same type as `x`.

