# Keras -- Deeper Systems

For the original Keras, click [here](https://github.com/fchollet/keras)


## Differences between keras_ds and keras

- `keras_ds.metrics.Metric` abstract class to implement more flexible metrics
- `keras_ds.callbacks.Tracker` callback to keep track of metrics
- The interrupt menu system (See `keras_ds.interrupt`), including the `safe_training` parameter on `fit` and `fit_generator`
- Better callback printing. Use `callbacks.printer` to print anything when using callbacks
- Other minor tweaks
