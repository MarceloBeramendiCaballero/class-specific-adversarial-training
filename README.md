<h1> Studying adversarial examples with class-specific adversarial training

 <h2>Description</h2>

Why does adding insignificant amounts of noise, which are imperceptible to the human eye, drastically decrease the accuracy of image classification models? In order to answer this question, it would be useful to think about the effect of noise in neural network’s semantic representations of images. With that goal in mind, I developed a method in which models are trained on their regular training set plus adversarial examples of only a few classes. We found that while this form of adversarial training only improved the performance on adversarial examples of the selected classes in models like LeNet, models like MobileNetV2 improved their performance across adversarial examples of every single class, even though the training set did not include adversarial examples of all classes.

<p align="center">
  <img src="https://i.imgur.com/VMT89HJ.png" height="70%" width="70%"/>
