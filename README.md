# Cifar10_TransferLerining
Cifar10_TransferLerining: CNN architectures on Cifar 10 dataset


Inception V3 with weights trained on Imagent was used. The weights were forzen so that it won't change while we train the final added layers. 2 dense layers were added with dimensions 512 and 10 respectively. Lambda layer is used to resize the cifar image to match the input of Inception v3.
Run only for 5 epochs before saving
