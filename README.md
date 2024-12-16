# Statistical Characteristics Estimation for Underwater Image Restoration (SCEIR)


## Requirements
We implement all the experiments in the following environment.
1. python=3.9.12
2. torch==1.10.2
3. torchvision=0.11.3
4. PIL, tqdm


For stable running, torch>=1.8.1 and torchvision>=0.4.0 are recommended.

## Running

### Testing
Put the test images into "./test_input" or change the option "--test_input" to your image dir

```
python test.py --save_extra --gpu YOUR_DEVICE --test_input YOUR_IMAGE_DIR
```

### Training
Put the pair training images into "./dataset", and changes the option "--train_raw", "--train_ref", 
"--eval_raw" and "--eval_ref" to the relevant path.

```
python train.py --gpu YOUR_DEVICE
```

