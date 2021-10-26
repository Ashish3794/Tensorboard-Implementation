# Tensorboard-Implementation
Using Tensorboard for learning purpose

The code uses MNIST dataset and implements a deep learning model to identify handwritten digits from 0 to 9.
Tensorboard callbacks, checkpoints and logs are also added in the code.

The artifacts folder consist of checkpoints and saved models with unique names basd on time stamps.
logs_dir folder contains tensorboard logs



Commands:

```Bash
conda activate ./envs
python src/training.py
tensorboard --logdir=logs_dir/tensorboard_logs
```
