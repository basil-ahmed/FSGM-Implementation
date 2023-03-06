# FSGM-Implementation

- Implemented in PyTorch
- Works by adding a small amount of random noise to the input data
- The attack computes the gradient of the loss function with respect to the input data, and then adds noise to the input in the direction of the gradient, while constraining the size of the noise to be small.
- Often used as a benchmark for evaluating the robustness of machine learning models

<img width="538" alt="image" src="https://user-images.githubusercontent.com/90772853/223028438-7e6cfd83-2fc0-4064-ac09-4759b7721a56.png">


## My Output:

![FSGM Implementation (2)](https://user-images.githubusercontent.com/90772853/223028102-f15eef0a-c8e3-457f-8013-f2bd255e62b8.png)

![FSGM Implementation](https://user-images.githubusercontent.com/90772853/223028120-01721a14-cddb-4af7-aa49-ce441e14941a.png)

## Torchattacks Library Output:

![FSGM_TorchAttack](https://user-images.githubusercontent.com/90772853/223028195-38fddcd4-b703-4a45-ad7b-1a38afa4211f.png)
