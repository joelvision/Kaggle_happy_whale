# Kaggle Competition

## Happywhale - Whale and Dolphin Identification
- Link : https://www.kaggle.com/competitions/happy-whale-and-dolphin
- Goal : Identifying whale fins and identifying "unidentified" not in test dataset.
- Stack : Python, Pytorch, Pytorch-lightning

## Competition scenario
- Firstly, My team found very small whale in images
- So we focus on whale for accurate identification
- We used an annotation tool called "labelme" to create our own yolo data.
- It was an inaccessible problem due to simple classification problems such as the MNIST.
- Because the Test dataset has an object called "unidentitfied" that Train dataset does not have.
- So we try to metric learning.
    - We used an "Arcface", which worked. Through this, we achieved a performance improvement of about 0.4.

## Result
127 / 1588 (Sliver Medal)
