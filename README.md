# Video-Prediction-using-PyTorch
![Alt Text](/images/mnist_gif.gif)
Repository for frame prediction on the MovingMNIST dataset using seq2seq ConvLSTM.

## Getting started
1. Install the libraries below

```
python=3.6.8
torch=1.1.0
torchvision=0.3.0
pytorch-lightning=0.7.1
matplotlib=3.1.3
tensorboard=1.15.0a20190708
```

2. Clone this repo

```bash
git clone https://github.com/abhilashabhilash3/Video-Prediction-using-PyTorch-Lightning.git
cd ./Video-Prediction-using-PyTorch-Lightning
```

3. Run main.py
```bash
python main.py
```

4. Navigate to http://localhost:6006/ for visualizing results


## Results
The first row displays model predictions, the second row the ground truth and the third row the absolute error on a pixel-level. The first 8 columns are the input, followed by output in the final 8 columns. This matches the output from the Tensorboard logging. 

### Initial results (500 steps)
![Initial](/images/epoch0_500steps.png)


### After half an epoch (2500 steps)
![halfepoch](/images/epoch0_2500steps.png)


