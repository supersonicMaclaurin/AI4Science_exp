### AI4Science 

### ZS-DeconvNet: Image Super-Resolution in AI4Science
ZS-DeconvNet is an  zero-shot deconvolution network crafted to elevate the resolution and signal-to-noise ratio (SNR) of microscopy images, thereby significantly improving the clarity and quality of biological observations. 

#### Experiment setup
- PC with an Intel Core i7-10700 processor and an NVIDIA RTX 3090ti GPU
- TensorFlow 2.5.0 and
- Python 3.9.7

Training was conducted using the Adam optimizer with an initial learning rate of 5e-4, which decays by a factor of 0.5 every 10,000 iterations.
A batch size of 4 was utilized for the training process, which generally encompasses 50,000 iterations.

#### file structure
|--- reproduce_model  // my reproduced model

|--- test_results     // my test results of wide_field_images and Structured Illumination Microscopy (SIM) imaging of clathrin-coated pits (CCPs)
