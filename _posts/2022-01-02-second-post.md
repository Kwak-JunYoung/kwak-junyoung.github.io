---
title: "ML Models historical review"
date: 2022-01-02
categories: MachineLearning
---


<b>2012 - AlexNet</b>
<ul>
<li>When an image of 224 * 224 is given, classifying it will be the objective</li>
<li>The first trial of using deep learning for image classification</li>
<li>
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FlapGo%2Fbtrozw1U3y8%2FpIgFhOeUuWCf170VvnXAV0%2Fimg.png">
</li>
</ul>  
<b>2013 - DQN</b>
<ul>
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fdqd83Z%2FbtroxkBnM4S%2FnnbHQvtfNrMPA1znmVw7Bk%2Fimg.png">
</li>
</ul>  
<b>2014 - Encoder / Decoder, Adam</b>
<ul>
<li><b>Encoder / Decoder</b></li>
<ul>
<li>To solve Neural Machine Translation(NMT).</li>
<li>Google translator is the most famous example.</li>
<li>When a sequence of language A is given, encode this sequence into a vector, and that encoded vector will be decoded to another sequence of language B.</li>
<li><img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FmcmQv%2FbtrouzsgEC8%2FJ1jJuFQ4p726DAcWkQLdH1%2Fimg.png"></li>
</ul>  
<li><b>Adam</b></li>
<ul>
<li>Adaptive Momentum Optimizer</li>
<li>Best optimizer so far</li>
<li><img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2F81R87%2Fbtrotka5i3W%2FZd68rgvsLJMPlQGTKHguEk%2Fimg.png"></li>
</ul>
</ul>
2015 - Generative Adversarial Network(GAN) / ResNet
<ul>
<li>Generative Adversarial Network(GAN)</li>
<ul>
<li>Very important, will be dealt emphasized.</li>
<li>A network makes a generator and a discriminator and starts learning.</li>
<li><img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fb2vP0m%2FbtrozxftELs%2FDkdyXzKQV1EX0wFLrZwffK%2Fimg.png"></li>
</ul>
<li><strong>Residual Networks(ResNet)</strong></li>
<ul>
<li>Made possible deep learning actually be <strong>deep </strong>learning</li>
<li>Accumulating multiple networks actually damaged its performance, but ResNet improved this defect</li>
<li><img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FcxzvHI%2FbtrozwAR3yW%2FOSojfeGR99yFo4j0z8DKZK%2Fimg.png"></li>
</ul>
</ul>
<b>2017 - Transformer</b>
<ul>
<li>From thesis: Attention Is All You Need</li>
<li>Very important, will be dealt emphasized.</li>
<li><img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbEf6vi%2Fbtrosbebgd2%2FSQU3UaI6c9C46KlutWxfJ0%2Fimg.png"></li>
</ul>  
<b>2018 - Bidirectional Encoder Representations from Transformers(BERT)</b>
<ul>
<li>Fine-tuned NLP models</li>
<li><img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Frc9TX%2FbtroswCQMIF%2F5tk4KEBtTaVPCopxDg8s71%2Fimg.png"></li>
</ul>
<b>2019 - BIG Language Models</b>
<ul>
<li>Best fine-tuned NLP Models</li>
<li>Can make sequential models(sentence, program, graph) with little fine-tuning</li>
</ul>
<b>2020 - Self Supervised Learning</b>
<ul>
<li>You want to solve a classification problem with limited training data. Usually, giving modifications to a model by manipulating parameters, layers, loss functions.</li>
<li>What makes this different is that it will take advantage of data that is not labeled.</li>
</ul>
