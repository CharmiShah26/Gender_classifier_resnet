# Gender Classifier using ResNet
Classifying gender from given set of input data consisting of men &amp; women images using ResNet152V2

* Base model: ResNet152V2 with imagenet weights
* Transfer learning in two different ways:  
 A. One-step transfer learning without freezing the base layer  
 B. Two-step transfer learning (first only the output layer, then fine-tuning)
* Got a 87-88% test accuracy with (B) way of transfer learning
