## CartPole-v0 OpenGym environment
-Using Jupyter Notebook File

### **Importing File:**
```sh
import gym
import keras	# Backend Theano, see below for `config keras.json`
import random
import math
import numpy as np
from collections import deque
```
### **Some configuration before setup:**
#### keras.json [file path: /Users/`your_system_username`/.keras]
```sh
{
    "floatx": "float32",
    "epsilon": 1e-07,
    "backend": "theano",
    "image_data_format": "channels_last"
}
```
