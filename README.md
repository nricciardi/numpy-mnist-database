# MNIST grayscale dataset for NumPy

```python
import mnist

x_train, y_train, x_test, y_test = mnist.grayscale_mnist_sets()
# or
x_train, y_train, x_test, y_test = mnist.binary_mnist_sets()

# x_train.shape: (60000, 28, 28) 
# y_train.shape: (60000,) 
# x_test.shape: (10000, 28, 28) 
# y_test.shape: (10000)
```

If you want, you can only extract datasets running `mnist.py`

Default configuration:

```python
MNIST_ZIP_FILE = "./mnist/mnist.zip"
OUTPUT_DIR = "./mnist"
DATASET_DIR = OUTPUT_DIR
```
