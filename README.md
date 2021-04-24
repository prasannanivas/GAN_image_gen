# **GANs for creating fake football celebrations** 

The goal of this project was to explore how GANs work and test training a GAN on my own project.

---
I have a write up on my blog if you're interested. With this in mind I'll keep the README as a basic intro and instructions for setup. 

http://www.machinelearninginsport.co.uk/gans.html

[//]: # (Image References)

[image1]: ./data/ron.jpg "example celebration"
[image2]: ./results/fake_celebrate000.png "1 epoch"
[image3]: ./results/fake_celebrate499.png "499 epoch"

---

There are two GAN implementations included. One is a pytorch implementation based on the course content from "Deep Learning and Computer Vision A-Z:OpenCV, SSD & GANs" by Hadelin de Ponteves and Kirill Eremenko which is available on Udemy.  
The second is an equivalent implementation coded in keras. 

To train these GANs on your own data you will need to source data and add to the data file. I've included some example images that I used to train the model discussed in my blog. I scrapped these from the internet and so have no included the whole set, but you could replace this with whatever you required. 

![alt text][image1]

You can also adjust how often the example result images are saved to file. Again I've included a couple of example images from different stages of training as examples. 

![alt text][image2]

![alt text][image3]