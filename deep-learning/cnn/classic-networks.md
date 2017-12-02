# LeNet - 5
#### Structure:
conv(f=5x5,s=1)-pooling(f=2,s=2)-conv(f=5x5,s=1)-pooling(f=2,s=2)-fc(120)-fc(84).
![](/assets/Screen Shot 2017-12-02 at 15.13.22.png)

5 layers: 2 convs, 2 fc, 1 output
Totally, 60K parameters.


# Alex - Net

![](/assets/Screen Shot 2017-12-02 at 15.12.59.png)
7 layers: 4 convs, 2 fc, 1 output
Totally, 60 M parameters.

# VGG - 16

![](/assets/Screen Shot 2017-12-02 at 15.24.38.png)
convs: 3x3, stride = 1,
max-pooling: 2x2, stride = 2,
16 layers: 13 convs, 2 fc, 1 output
Totally, 138M parameters.

# ResNets
Skip connections, can help much deeper networks.
![](/assets/Screen Shot 2017-12-02 at 15.38.15.png)

![](/assets/Screen Shot 2017-12-02 at 15.39.05.png)

# Inception Neworks
Using 1x1 convolution to reduce computational cost
  
![](/assets/Screen Shot 2017-12-02 at 16.03.59.png)