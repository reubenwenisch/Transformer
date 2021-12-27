# ViT-pytorch
 
## Attention

The Attention mechanism consists of
- Query
- Key
- Value

Consider the input image subdivided into grids. The Query part in an image is basically a section or one grid of the image. This query is multiplied with key and attention scores are obtainted. This is multiplied back with the other parts of the image and a probability score is obtained called the attention output. 

## MLP
MLP is multi Layered Perceptron. This basically has two fully connected layers and a dropout mechanism in between. The init values are sampled from a uniform distribution.

## Blocks
There are two types of blocks in a sequence to sequence transformer netwrork
* An Encoder Block
* A Decoder Block

## Embeddings
The embeddings are used to compare to other patches of the image and obtain their relationships. So essentially the embedding contains the input x along with the positional embeddings about the context.


