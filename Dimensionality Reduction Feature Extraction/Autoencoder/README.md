# Autoencoder

## what is autoencoder?
> Autoencoder is essentially a Neural Network that replicates the input layer in its output, after coding it in-between.

## How it work?
1. First check dataset is null or not.if not then we have to check is there any variables is unneed or not id is there we have to remove them.

2. Then we have to encode catagorical variable to one hot encoding and also Scale variables into 0 and 1 range 

3. Then we have to choose size of our encoded representations.

4. Create autoencoding model in step wise input,encoding,decoding.
