<img src="https://raw.githubusercontent.com/EfficientDL/book/main/images/book-cover.png" alt="Efficient Deep Learning book cover" 
  style="float:right;width:275px;margin-left:20px;margin-bottom:20px;">

<br/>

Please link to this site using [https://efficientdlbook.com](https://efficientdlbook.com).

- [Authors](#authors)
- [Download](#download)
- [Introduction](#introduction)
- [Table of Contents](#table-of-contents)
- [Projects / Codelabs / Tutorials](#projects--codelabs--tutorials)
- [The Minimally Qualified Reader](#the-minimally-qualified-reader)
- [Subscribe for Updates](#subscribe-for-updates)
- [Report errata and feedback.](#report-errata-and-feedback)

## Authors
* Gaurav Menghani ([GitHub](https://github.com/reddragon), [LinkedIn](https://www.linkedin.com/in/gauravmenghani/), [Twitter](https://twitter.com/GauravML), [Website](https://gaurav.ai))
* Naresh Singh ([GitHub](https://github.com/NareshPS), [LinkedIn](https://www.linkedin.com/in/naresh-singh-15916b17/), [Twitter](https://twitter.com/_NareshPS))

If you are interested in collaborating with us in any aspect of developing this book, please feel free to reach out to us at: [hello@efficientdlbook.com](mailto:hello@efficientdlbook.com).

## Download
We have included the PDFs of some of the chapter drafts for your review (Chapter [1](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%201%20-%20Introduction.pdf), [2](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%202%20-%20Compression%20Techniques.pdf), [3](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%203%20-%20Learning%20Techniques.pdf), [4](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%204%20-%20Efficient%20Architectures.pdf)). Please be warned that the content is in an initial stage, and might contain errors. Any feedback is appreciated though.

## Introduction

<p align="justify">
The field of Deep Learning has progressed exponentially, and so has the footprint of ML models like BERT, GPT-3, ResNet, etc. While they work great, training and deploying these large (and growing) models in production is expensive. You might want to deploy your face filter model on smartphones to let your users add a puppy filter on their selfies. But it might be too big or too slow, or you might want to improve the quality of your cloud-based spam detection model but you don’t want to pay for a bigger cloud VM to host a more accurate but larger model. What if you don’t have enough labeled data for your models, or can’t manually tune your models? All this is daunting!
</p>

<p align="justify">
<b>What if you could make your models more efficient: use less resources</b> (model size, latency, training time, data, manual involvement) <b>and deliver better quality</b> (accuracy, precision, recall, etc.). That sounds wonderful! But how?
</p> 

<p align="justify">
This book will go through algorithms and techniques used by researchers and engineers at Google Research, Facebook AI Research (FAIR), and other eminent AI labs to train and deploy their models on devices ranging from large server-side machines to tiny microcontrollers. In this book we present a balance of fundamentals as well as practical know-how to fully equip you to go ahead and optimize your model training and deployment workflows such that your models perform as well or better than earlier, with a fraction of resources. We also will present deep dives into popular models, infrastructure, and hardware, along with challenging projects to test your skills.
</p>

##  Table of Contents

The table of contents is as follows.

**Part I: Introduction to Efficient Deep Learning**  

1. **Introduction [(PDF)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%201%20-%20Introduction.pdf)**
   - Introduction to Deep Learning
   - Efficient Deep Learning
   - Mental Model of Efficient Deep Learning
   - Summary

**Part II: Effciency Techniques**

{:start="2"}
1. **Introduction to Compression Techniques [(PDF)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%202%20-%20Compression%20Techniques.pdf)**
   - An Overview of Compression
   - Quantization
   - Exercises: Compressing images from the Mars Rover
   - Project: Quantizing a Deep Learning Model
   - Summary


2. **Introduction to Learning Techniques [(PDF)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%203%20-%20Learning%20Techniques.pdf)**
    - Learning Techniques and Efficiency
    - Data Augmentation
      - Project: Increasing the accuracy of an image classification model with Data Augmentation.
      - Project: Increasing the accuracy of a text classification model with Data Augmentation.
    - Distillation
      - Project: Increasing the accuracy of an speech identification model with Distillation.
    - Summary

3. **Efficient Architectures [(PDF)](https://github.com/EfficientDL/book/raw/main/book/%5BEDL%5D%20Chapter%204%20-%20Efficient%20Architectures.pdf)**
    - Embeddings for Smaller and Faster Models
      - Project: Using pre-trained embeddings to improve accuracy of a NLP task.
    - Learn Long-Term Dependencies Using Attention
      - Project: News Classification Using RNN and Attention Models
    - Efficient On-Device Convolutions
      - Project: Project: Snapchat-Like Filters for Pets
    - Summary

4. **Advanced Compression Techniques**
   - Pruning
   - Weight Clustering
   - Weight Sharing
   - Matrix Factorization
   - Project: Comparing Compression Techniques for optimizing a speech detection model.

5. **Advanced Learning Techniques**
   - Contrastive Learning
   - Unsupervised Pre-Training
   - Project: Learning to classify with 10% labels.
   - Curriculum Learning
  
6. **Automation**
   - Hyper-Parameter Tuning
     - Project: Multi-objective tuning to get a smaller and more accurate model.
   - AutoML
     - Project: Searching over model architectures for boosting model accuracy.
   - Compression Search
     - Project: Layer-wise Sparsity to achieve a pareto optimal model. 

**Part 3 - Infrastructure**

{:start="8"}
1.   **Software Infrastructure**
   - PyTorch Ecosystem
   - iOS Ecosystem
   - Cloud Ecosystems

2. **Hardware infrastructure**
   - GPUs
   - Jetson
   - TPU
   - M1 / A4/5?
   - Microcontrollers


**Part 3 - Applied Deep Dives**

{:start="10"}
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


## Projects / Codelabs / Tutorials

- Are available [here](https://github.com/EfficientDL/book/tree/main/codelabs). 

## The Minimally Qualified Reader
The minimally qualified reader is someone who has a basic understanding of ML and at least some experience of training deep learning models. They can do basic fine-tuning of models by changing common parameters, can make minor changes to model architectures, etc. and get the modified models to train to a good accuracy. However, they are running into problems with productionizing these models / want to optimize them further. This is primarily because the book does not teach deep learning basics, for which we would like to refer you to excellent resources like [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python), [Dive into Deep Learning](d2l.ai), etc. Any reader having this pre-requisite knowledge would be able to enjoy the book.

## Subscribe for Updates

<!-- Begin Mailchimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/classic-10_7_dtp.css" rel="stylesheet" type="text/css">
<style type="text/css">
	#mc_embed_signup{background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif;  width:500px;}
	/* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
	   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
</style>
<div id="mc_embed_signup">
<form action="https://gmail.us10.list-manage.com/subscribe/post?u=8ce6435a6f6a818244e576d76&amp;id=1aef314b39" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	
<div class="indicates-required"><span class="asterisk">*</span> indicates required</div>
<div class="mc-field-group">
	<label for="mce-EMAIL">Email Address  <span class="asterisk">*</span>
</label>
	<input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
</div>
<div class="mc-field-group">
	<label for="mce-NAME">Name </label>
	<input type="text" value="" name="NAME" class="" id="mce-NAME">
</div>
	<div id="mce-responses" class="clear foot">
		<div class="response" id="mce-error-response" style="display:none"></div>
		<div class="response" id="mce-success-response" style="display:none"></div>
	</div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_8ce6435a6f6a818244e576d76_1aef314b39" tabindex="-1" value=""></div>
        <div class="optionalParent">
            <div class="clear foot">
                <input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button">
                <p class="brandingLogo"><a href="http://eepurl.com/h1kUMP" title="Mailchimp - email marketing made easy and fun"><img src="https://eep.io/mc-cdn-images/template_images/branding_logo_text_dark_dtp.svg"></a></p>
            </div>
        </div>
    </div>
</form>
</div>
<script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script><script type='text/javascript'>(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='NAME';ftypes[1]='text';}(jQuery));var $mcj = jQuery.noConflict(true);</script>
<!--End mc_embed_signup-->

## [Report errata and feedback](https://github.com/EfficientDL/book/issues).

We welcome any errata / feedback / ideas. Please file them as an issue [here](https://github.com/EfficientDL/book/issues). Alternatively, write to us at [hello@efficientdlbook.com](mailto:hello@efficientdlbook.com).
