# InfoGAN

## Dependencies

This project currently requires the dev version of TensorFlow available on Github: https://github.com/tensorflow/tensorflow. As of the release, the latest commit is [79174a](https://github.com/tensorflow/tensorflow/commit/79174afa30046ecdc437b531812f2cb41a32695e).

In addition, please `pip install` the following packages:
- `prettytensor`
- `progressbar`

## Running Experiment

We provide the source code to run the MNIST example:

```bash
python launchers/run_mnist_exp.py
```

You can launch TensorBoard to view the generated images:

```bash
tensorboard --logdir logs/mnist
```