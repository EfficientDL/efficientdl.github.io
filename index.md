
Please link to this site using [https://efficientdlbook.com](https://efficientdlbook.com).

Twitter: [@GauravML](https://twitter.com/GauravML), [@_NareshPS](https://twitter.com/_NareshPS).


<img src="static/images/book-cover.png" alt="Efficient Deep Learning book cover" 
  style="float:right;width:250px;">

<p align="justify" style="margin: 0px 270px 5px 0px;">
The field of Deep Learning has progressed exponentially, and so has the footprint of ML models like BERT, GPT-3, ResNet, etc. While they work great, training and deploying these large (and growing) models in production is expensive. You might want to deploy your face filter model on smartphones to let your users add a puppy filter on their selfies. But it might be too big or too slow, or you might want to improve the quality of your cloud-based spam detection model but you don’t want to pay for a bigger cloud VM to host a more accurate but larger model. What if you don’t have enough labeled data for your models, or can’t manually tune your models? All this is daunting!
</p>

<p align="justify" style="margin: 0px 270px 5px 0px;">
What if you could make your models more efficient: use less resources (model size, latency, training time, data, manual involvement) and deliver better quality (accuracy, precision, recall, etc.). That sounds wonderful! But how?
</p> 

<p align="justify" style="margin: 0px 270px 5px 0px;">
This book will go through algorithms and techniques used by researchers and engineers at Google Research, Facebook AI Research (FAIR), and other eminent AI labs to train and deploy their models on devices ranging from large server-side machines to tiny microcontrollers. In this book we present a balance of fundamentals as well as practical know-how to fully equip you to go ahead and optimize your model training and deployment workflows such that your models perform as well or better than earlier, with a fraction of resources. We also will present deep dives into popular models, infrastructure, and hardware, along with challenging projects to test your skills.
</p>


##  Table of Contents

**Part I: Introduction to Efficient Deep Learning**  

1. **Introduction**
   - Introduction
   - Efficient Deep Learning
   - Mental Model of Efficient Deep Learning

**Part II: Effciency Techniques**

{:start="2"}
2. **Introduction to Compression Techniques**
   - Motivation
   - Quantization
   - Exercises: Compressing images from the Mars Rover.
   - Project: Optimizing an MNIST model with Quantization


3. **Introduction to Learning Techniques**
    - Motivation
    - Distillation
      - Project: Increasing the accuracy of an image classification model with Distillation.
    - Data Augmentation
      - Project: Increasing the accuracy of an image classification model with Data Augmentation.

4. **Efficient Architectures**
    - Motivation
    - Depthwise-Separable Layers
      - Project: Reducing model size and latency on Mobile for ConvNets.
    - Projections
      - Project: Small Text Classification models with Projections.
    - Hashing Trick
      - Project: Microsecond Scale Text Classification with the Hashing Trick.

5. **Automation**
   - Motivation
   - Hyper-Parameter Tuning
     - Project: Multi-objective tuning to get a smaller and more accurate model.
   - AutoML
     - Project: Searching over model architectures for boosting model accuracy.
   - Compression Search
     - Project: Layer-wise Sparsity to achieve a pareto optimal model. 

6. **Advanced Compression Techniques**
   - Pruning
  - Clustering / Matrix Factorization
  - Weight Sharing
  - Project: Comparing Compression Techniques for optimizing a speech detection model.


7. **Advanced Learning Techniques**
  - Contrastive Learning
  - Project: Learning to classify with 10% labels.
  - Federated Learning

**Part 3 - Applied Deep Dives**

{:start="8"}
8. **Deep-Dives: Deployment to Platforms** 
   - Mobile
     - Project: Deploying and benchmarking a tiny model with TFLite.
     - Microcontrollers
     - Project: Speech detection on a Microcontroller with TFMicro.
   - Web
     - Project: Face recognition on the Web with TensorFlow.JS.
   - Google Tensor Processing Unit (TPU)
     - Project: Training BERT with TPUs.
   - Summary

9. **Deep-Dives: Efficient Models**
    - BERT
      - Project: Training efficient BERT models.
    - MobileNet
    - EfficientNet architectures
      - Project: Comparing efficient mobile models on Mobile.
    - Speech Detection
      - Project: Efficient speech detection models.

**Part 4 - Software Infrastructure**

{:start="10"}
10.   **Software Infrastructure**
   - Tensorflow Ecosystem
   - PyTorch Ecosystem
   - iOS Ecosystem


### [Report errata and feedback](https://github.com/EfficientDL/book/issues).

Any issues you raise now may not make it into the printed version, but we will keep an updated PDF around (and the errata).


## Projects / Codelabs / Tutorials

- Are available [here](https://github.com/EfficientDL/book/tree/main/codelabs). 