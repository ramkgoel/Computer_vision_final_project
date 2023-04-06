Ideas for final project:

Vision Transformer (ViT)

Original Vision Transformer Paper: https://arxiv.org/pdf/2010.11929.pdf
Self-Supervised Vision Transformer Paper: https://arxiv.org/pdf/2104.14294.pdf

Basically a ViT is an image classification model. The idea is that it splits up the image into patches and uses those in the same way words are used in NLP transformers. Then regular transformer architecture is applied. It has the same functionality as CNN for image classification. 

The problem is that inductive biases such as translation-similar are not as well encapsulated in Transformer as much as CNN. But more training data outweighs the con of inductive biases.  
ViT needs a lot of training data. 
The original ViT paper has a lot of details on how to implement a ViT. 

We could try and implement a ViT (and a self-supervised ViT maybe?) and compare to CNN for image classification. 
I think we should say "ok we predict ViT will do badly given less data compared to CNN", and show how increasing amounts of data increase its accuracy. 

What image dataset should we use? 
