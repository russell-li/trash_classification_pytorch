# trash_classification_pytorch
Trash Classification Algorithm Based On Pytorch
## Details
The dataset I used is from kaggle, the link is https://www.kaggle.com/techsash/waste-classification-data

The dataset include 2 classes(Organic and recyclable).

We can find two mode in the code,  if feature extracting we just grad the last linear layer, if finetuning, we finetuning all parameters.

And more, I made a comparison with model trained with scratch.

You can find more parameters details in the code. 
## Performance
The best performance model is inceptionv3 based on finetuning, I test several algorithms below, the train history is:

squeezenet:Training complete in 37m 12s, Best val Acc: 0.954238

resnet:Training complete in 90m 16s, Best val Acc: 0.962992

densenet:Training complete in 97m 11s, Best val Acc: 0.962197

inceptionV3:Training complete in 61m 54s, Best val Acc: 0.964186

we can find inceptionv3 just need 60 minute and get the best accuracy.

## equirements
The code can be run in colab, I built it in colab.

## Algorithms
There are 6 classical algorithms you can chose to train the model, it include resnet50, alexnet, vgg, squeezenet, densenet and inceptionV3

## Acknowledgement
This work mostly built on pytorch offical [tutorials](https://pytorch.org/tutorials)
And [Sashaank Sekar provide the dataset in kaggle](https://www.kaggle.com/techsash/waste-classification-data)
