# Mastering Transformers, Second Edition

<a href="https://www.packtpub.com/product/mastering-transformers-second-edition/9781837633784"><img src="https://m.media-amazon.com/images/I/71nbaPZfXML._SL1500_.jpg" alt="Mastering Transformers, Second Edition" height="256px" align="right"></a>

This is the code repository for [Mastering Transformers, Second Edition](https://www.packtpub.com/product/mastering-transformers-second-edition/9781837633784), published by Packt.

**The journey from BERT to large language models and stable diffusion**

## What is this book about?

Transformer-based language models have dominated natural language processing studies and become a new paradigm. With this NLP transformers book, you’ll be able to implement multimodal solutions, including text-to-image (Stable Diffusion).

This book covers the following exciting features: 
* Focus on solving simple-to-complex NLP problems with Python
* Discover how to solve classification/regression problems with traditional NLP approaches
* Train a language model and explore how to fine-tune models to the downstream tasks
* Understand how to use transformers for generative AI and computer vision tasks
* Build transformer-based NLP apps with the Python transformers library
* Focus on language generation such as machine translation and conversational AI in any language
* Speed up transformer model inference to reduce latency

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1837633789) today!

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```python
from transformers import pipeline
classifier = pipeline("zero-shot-classification",
    model="facebook/bart-large-mnli")
sequence_to_classify = "I am going to france."
candidate_labels = ['travel', 'cooking', 'dancing']
classifier(sequence_to_classify, candidate_labels)
```

**Following is what you need for this book:**

Complete with step-by-step explanation and exploration of Stable Diffusion model with Python, you will start to understand how Stable Diffusion works and how the source code is organized to make your own advanced features, or even build one of your own complete standalone Stable Diffusion application.

With the following software and hardware list you can run all code files present in the book (Chapter 1-18).

### Software and Hardware List

| Chapter  | Software & Hardware required                                                                    | OS required             |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  	1-18   |   Programming language: Python                             			  | Windows, macOS, or Linux | 		
|  	1-18	   |   	Libraries: transformers, PyTorch, peft, trl                       | | 		
|  	1-18	   |   Jupyter Notebook                             			  | | 		

### Related products <Other books you may enjoy>
* Transformers for Natural Language Processing and Computer Vision  [[Packt]](https://www.packtpub.com/product/transformers-for-natural-language-processing-and-computer-vision-third-edition/9781805128724) [[Amazon]](https://www.amazon.com/Transformers-Natural-Language-Processing-Computer/dp/1805128728/ref=sr_1_1?s=books&sr=1-1)
  
* Mastering NLP from Foundations to LLMs  [[Packt]](https://www.packtpub.com/product/mastering-nlp-from-foundations-to-llms/9781804619186) [[Amazon]](https://www.amazon.com/Mastering-NLP-Foundations-LLMs-Techniques/dp/1804619183/ref=sr_1_1?s=books&sr=1-1)
  
## Get to Know the Authors
**Savas** has a strong background in computer engineering and natural language processing, having graduated from Istanbul Technical University with a degree in computer engineering and earned a Ph.D. in NLP from Trakya University. He has spent over 20 years working in the field of artificial intelligence as a researcher and lecturer, with a focus on machine learning, deep learning, and natural language processing. Throughout his career, he has made numerous contributions to the natural language processing community through the development of open-source software and resources. In addition to his academic pursuits, he has also worked as a consultant for AI companies, providing guidance on their research and development projects and contributing to a number of industrial R&D-funded projects over the past 15 years. His areas of interest within the field of AI include explainable AI, zero-shot learning, natural language understanding and generation, and semantic search. Currently, he is serving as an Associate Professor at Istanbul Bilgi University and a Visiting Lecturer at Toronto Metropolitan University.

**Meysam** is a Senior AI Researcher at Ultimate. He has been a consultant for Turkey's leading telecommunication and banking companies. He has also worked on various projects, including natural language understanding and semantic search.
