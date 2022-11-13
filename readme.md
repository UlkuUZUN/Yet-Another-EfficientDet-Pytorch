# Cycle-Spinning (CS) method employement in Yet Another EfficientDet Pytorch

The pytorch re-implement of the official [EfficientDet](https://github.com/google/automl/tree/master/efficientdet) with Cycle-Spinning (CS) method employement performance in real time. (Paper link: <https://ieeexplore.ieee.org/document/9832606>)

## Extra information for cycle-spinning please visit: https://github.com/UlkuUZUN/Cycle-Spinning-NN

In the original code, the Cycle-Spinning (CS) method has been employed to the model.py file under EfficientNet folder to work with 1 and 2 shifts in the first convolution process. In our experiments it is seen that CS method employement gets good results if it works with first convolution and samll shifts up to 3 shifts.

