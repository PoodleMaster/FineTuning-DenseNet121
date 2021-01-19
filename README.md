# ■FineTuning (DenseNet121)
Tried **`MNIST`** using the **DenseNet121** model that has been trained with ImageNet.

# ■Requirements
Google Colab

# ■How to FineTuning
The training data of MNIST is 28 x 28 x 1ch, and the input layer of DenseNet121 is over32 x over32 x 3ch, so it is necessary to match these. There are two ways to match.

## ➊How to match MNIST images to the DensNet121 input tensor
[Click here for details (See .ipynb)](https://github.com/PoodleMaster/FineTuning-DenseNet121/blob/main/%E3%80%90FineTuning%E3%80%91DenseNet121(64%2C%2064%2C%203ch)%20NG56.ipynb)

![pic](https://user-images.githubusercontent.com/69660581/104994891-b41f9780-5a68-11eb-97b5-b37fbe7d9cae.png)

## ➋How to change the input layer of a model
[Click here for details (See .ipynb)](https://github.com/PoodleMaster/FineTuning-DenseNet121/blob/main/%E3%80%90FineTuning%E3%80%91DenseNet121(64%2C%2064%2C%201ch)%20NG65.ipynb)

![pic](https://user-images.githubusercontent.com/69660581/104995325-753e1180-5a69-11eb-8b94-5ebe374dbcaa.png)

# ■Contributing
Contributions, issues and feature requests are welcome.

# ■Author
Github: PoodleMaster

# ■License
Check the LICENSE file.
