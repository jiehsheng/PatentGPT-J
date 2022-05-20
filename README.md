# PatentGPT-J 
 
* PatentGPT-J models are pre-trained with patent corpus and based on the [GPT-J-6B & Mesh Transformer JAX](https://github.com/kingoflolz/mesh-transformer-jax). 

* Model files
  * [PatentGPT-J-279M](https://huggingface.co/patent/patentgpt-j-279M)
  * [PatentGPT-J-456M](https://huggingface.co/patent/patentgpt-j-456M)
  * [PatentGPT-J-1.6B](https://huggingface.co/patent/patentgpt-j-1.6B)
  * sample code for using the these models for inference (see the following Sentiment Analysis experiment)

* Experiments
  * Autocomplete Effectiveness (AE) ratio 
    * [Inspecting AE ratio and keystroke distribution (data: ipg22)](https://huggingface.co/spaces/patent/demo1)
    * [Inspecting AE ratio and keystroke distribution (data: ipg220104)](https://huggingface.co/spaces/patent/demo2)
    * [Inspecting AE ratio and keystroke distribution (data: unicorn text)](https://huggingface.co/spaces/patent/demo3)
    
  * Unreasonable effectiveness in Few-Shot Learning: [Sentiment_Analysis_by_PatentGPT_J.ipynb](https://github.com/jiehsheng/PatentGPT-J/blob/master/Sentiment_Analysis_by_PatentGPT_J.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jiehsheng/PatentGPT-J/blob/master/Sentiment_Analysis_by_PatentGPT_J.ipynb)
