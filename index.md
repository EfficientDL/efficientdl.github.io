<head>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GLN4VNTGHS"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GLN4VNTGHS');
</script>
</head>

Please link to this site using [https://efficientdlbook.com](https://efficientdlbook.com).

Twitter: [@GauravML](https://twitter.com/GauravML), [@_NareshPS](https://twitter.com/_NareshPS).


<img src="static/images/book-cover.png" alt="Efficient Deep Learning book cover" 
  style="float:right;width:250px;margin-left:20px;margin-bottom:20px;">

<p align="justify">
The field of Deep Learning has progressed exponentially, and so has the footprint of ML models like BERT, GPT-3, ResNet, etc. While they work great, training and deploying these large (and growing) models in production is expensive. You might want to deploy your face filter model on smartphones to let your users add a puppy filter on their selfies. But it might be too big or too slow, or you might want to improve the quality of your cloud-based spam detection model but you don’t want to pay for a bigger cloud VM to host a more accurate but larger model. What if you don’t have enough labeled data for your models, or can’t manually tune your models? All this is daunting!
</p>

<p align="justify">
What if you could make your models more efficient: use less resources (model size, latency, training time, data, manual involvement) and deliver better quality (accuracy, precision, recall, etc.). That sounds wonderful! But how?
</p> 

<p align="justify">
This book will go through algorithms and techniques used by researchers and engineers at Google Research, Facebook AI Research (FAIR), and other eminent AI labs to train and deploy their models on devices ranging from large server-side machines to tiny microcontrollers. In this book we present a balance of fundamentals as well as practical know-how to fully equip you to go ahead and optimize your model training and deployment workflows such that your models perform as well or better than earlier, with a fraction of resources. We also will present deep dives into popular models, infrastructure, and hardware, along with challenging projects to test your skills.
</p>

### [Report errata and feedback](https://github.com/EfficientDL/book/issues).

We welcome any errata / feedback / ideas. Please file them as an issue [here](https://github.com/EfficientDL/book/issues).


##  Table of Contents

**Part I: Introduction to Efficient Deep Learning**  

1. **[Introduction (pdf)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%201%20-%20Introduction.pdf)**
   - Introduction to Deep Learning
   - Efficient Deep Learning
   - Mental Model of Efficient Deep Learning
   - Summary

**Part II: Effciency Techniques**

{:start="2"}
1. **[Introduction to Compression Techniques (pdf)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%202%20-%20Compression%20Techniques.pdf)**
   - An Overview of Compression
   - Quantization
   - Exercises: Compressing images from the Mars Rover
   - Project: Quantizing a Deep Learning Model
   - Summary


2. **[Introduction to Learning Techniques (pdf)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%203%20-%20Learning%20Techniques.pdf)**
    - Learning Techniques and Efficiency
    - Data Augmentation
      - Project: Increasing the accuracy of an image classification model with Data Augmentation.
      - Project: Increasing the accuracy of a text classification model with Data Augmentation.
    - Distillation
      - Project: Increasing the accuracy of an speech identification model with Distillation.
    - Summary

3. **[Efficient Architectures (pdf)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%204%20-%20Efficient%20Architectures.pdf)**
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
8. **Deep-Dives: Deployment to Tensorflow Platforms** 
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


## Projects / Codelabs / Tutorials

- Are available [here](https://github.com/EfficientDL/book/tree/main/codelabs). 