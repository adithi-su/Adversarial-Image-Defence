# Adversarial-Image-Defence
Adversarial examples are specialised inputs created with the purpose of confusing a neural network, resulting in the misclassification of a given input. These inputs are indistinguishable to the human eye, but cause the network to fail to identify the contents of the image. The fast gradient sign method attack is a white box attack whose goal is to ensure misclassification. A white box attack is where the attacker has complete access to the model being attacked. <br>
Adversarial example using FGSM.ipynb : Implementing Fast Gradient Sign Method, or FGSM, for generating adversarial noise -
```
$η=ϵ sign(∇ₓ J(θ,x,y)) $
```
Defending Against Adversarial Attacks.ipynb : ((On-going)
<ul> <li> Method 1: To reduce the impact of the attack, training the model on a given dataset, generating a set of adversarial images, and then fine-tuning the model on the adversarial images </li>
  <li>Method 2: Generating mixed batches of both the original training images and adversarial images, followed by fine-tuning the neural network on these mixed batches
</li> </ul>

 
