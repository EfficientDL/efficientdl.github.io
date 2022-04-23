<img src="https://raw.githubusercontent.com/EfficientDL/book/main/images/book-cover.png" alt="Efficient Deep Learning book cover" 
  style="float:right;width:275px;margin-left:20px;margin-bottom:20px;">


- [Authors](#authors)
- [Introduction](#introduction)
  - [The Minimally Qualified Reader](#the-minimally-qualified-reader)
  - [Report errata and feedback.](#report-errata-and-feedback)
- [Table of Contents](#table-of-contents)
- [Projects / Codelabs / Tutorials](#projects--codelabs--tutorials)

## Authors
* Gaurav Menghani ([GitHub](https://github.com/reddragon), [LinkedIn](https://www.linkedin.com/in/gauravmenghani/), [Twitter](https://twitter.com/GauravML), [Website](https://gaurav.ai))
* Naresh Singh ([GitHub](https://github.com/NareshPS), [LinkedIn](https://www.linkedin.com/in/naresh-singh-15916b17/), [Twitter](https://twitter.com/_NareshPS))

If you are interested in collaborating with us in any aspect of developing this book, please feel free to reach out to us at: [hello@efficientdlbook.com](mailto:hello@efficientdlbook.com).

## Introduction

<p align="justify">
The field of Deep Learning has progressed exponentially, and so has the footprint of ML models like BERT, GPT-3, ResNet, etc. While they work great, training and deploying these large (and growing) models in production is expensive. You might want to deploy your face filter model on smartphones to let your users add a puppy filter on their selfies. But it might be too big or too slow, or you might want to improve the quality of your cloud-based spam detection model but you don’t want to pay for a bigger cloud VM to host a more accurate but larger model. What if you don’t have enough labeled data for your models, or can’t manually tune your models? All this is daunting!
</p>

<p align="justify">
What if you could make your models more efficient: use less resources (model size, latency, training time, data, manual involvement) and deliver better quality (accuracy, precision, recall, etc.). That sounds wonderful! But how?
</p> 

<p align="justify">
This book will go through algorithms and techniques used by researchers and engineers at Google Research, Facebook AI Research (FAIR), and other eminent AI labs to train and deploy their models on devices ranging from large server-side machines to tiny microcontrollers. In this book we present a balance of fundamentals as well as practical know-how to fully equip you to go ahead and optimize your model training and deployment workflows such that your models perform as well or better than earlier, with a fraction of resources. We also will present deep dives into popular models, infrastructure, and hardware, along with challenging projects to test your skills.
</p>

### The Minimally Qualified Reader
The minimally qualified reader is someone who has a basic understanding of ML and at least some experience of training deep learning models. They can do basic fine-tuning of models by changing common parameters, can make minor changes to model architectures, etc. and get the modified models to train to a good accuracy. However, they are running into problems with productionizing these models / want to optimize them further. This is primarily because the book does not teach deep learning basics, for which we would like to refer you to excellent resources like [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python), [Dive into Deep Learning](d2l.ai), etc. Any reader having this pre-requisite knowledge would be able to enjoy the book.

### [Report errata and feedback](https://github.com/EfficientDL/book/issues).

We welcome any errata / feedback / ideas. Please file them as an issue [here](https://github.com/EfficientDL/book/issues). Alternatively, write to us at [hello@efficientdlbook.com](mailto:hello@efficientdlbook.com).


##  Table of Contents

The table of contents is as follows. We have also included PDFs of some of the chapter drafts for your review. Please be warned that the content is in an initial stage, and might contain errors. Any feedback is appreciated though.

**Part I: Introduction to Efficient Deep Learning**  

1. **[Introduction (draft pdf)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%201%20-%20Introduction.pdf)**
   - Introduction to Deep Learning
   - Efficient Deep Learning
   - Mental Model of Efficient Deep Learning
   - Summary

**Part II: Effciency Techniques**

{:start="2"}
1. **[Introduction to Compression Techniques (draft pdf)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%202%20-%20Compression%20Techniques.pdf)**
   - An Overview of Compression
   - Quantization
   - Exercises: Compressing images from the Mars Rover
   - Project: Quantizing a Deep Learning Model
   - Summary


2. **[Introduction to Learning Techniques (draft pdf)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%203%20-%20Learning%20Techniques.pdf)**
    - Learning Techniques and Efficiency
    - Data Augmentation
      - Project: Increasing the accuracy of an image classification model with Data Augmentation.
      - Project: Increasing the accuracy of a text classification model with Data Augmentation.
    - Distillation
      - Project: Increasing the accuracy of an speech identification model with Distillation.
    - Summary

3. **[Efficient Architectures (draft pdf)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%204%20-%20Efficient%20Architectures.pdf)**
    - Motivation
    - Embeddings for Smaller and Faster Models
      - Project: Using pre-trained embeddings to improve accuracy of a NLP task.
    - Learn Long-Term Dependencies Using Attention
      - Project: News Classification Using RNN and Attention Models
    - Efficient On-Device Convolutions
      - Project: Project: Snapchat-Like Filters for Pets
    - Summary

4. **Automation**
   - Motivation
   - Hyper-Parameter Tuning
     - Project: Multi-objective tuning to get a smaller and more accurate model.
   - AutoML
     - Project: Searching over model architectures for boosting model accuracy.
   - Compression Search
     - Project: Layer-wise Sparsity to achieve a pareto optimal model. 

5. **Advanced Compression Techniques**
   - Pruning
   - Clustering / Matrix Factorization
   - Weight Sharing
   - Project: Comparing Compression Techniques for optimizing a speech detection model.


6. **Advanced Learning Techniques**
  - Contrastive Learning
  - Project: Learning to classify with 10% labels.
  - Federated Learning

**Part 3 - Applied Deep Dives**

{:start="8"}
1. **Deep-Dives: Tensorflow Platforms** 
   - Mobile
     - Project: Benchmarking a tiny on-device model with TFLite.
   - Microcontrollers
     - Project: Speech detection on a microcontroller with TFMicro.
   - Web
     - Project: Face recognition on the web with TensorFlow.JS.
   - Google Tensor Processing Unit (TPU)
     - Project: Training BERT efficiently with TPUs.
   - Summary

2. **Deep-Dives: Efficient Models**
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


## Projects / Codelabs / Tutorials

- Are available [here](https://github.com/EfficientDL/book/tree/main/codelabs). 
