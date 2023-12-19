# ERA_S11
## Task : CIFAR 10 dataset classification using GRADCAM

### Files : Main_repo : https://github.com/sunandhini96/MAIN_Repo/tree/main

## Visualization after applying augmentation on cifar 10 dataset : 

![image](https://github.com/sunandhini96/ERA_S11/assets/63030539/3e0c672a-204d-410a-8142-648cff70b1c9)

## Summary of the model: 
```

================================================================
Total params: 11,173,962
Trainable params: 11,173,962
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 11.25
Params size (MB): 42.63
Estimated Total Size (MB): 53.89
----------------------------------------------------------------
```
## Training Logs:

EPOCH: 0
Loss=1.323206901550293 LR=0.0088780490797546 Batch_id=97 Accuracy=44.62: 100%|██████████| 98/98 [00:41<00:00,  2.33it/s]

Test set: Average loss: 0.0064, Accuracy: 2934/10000 (29.34%)

EPOCH: 1
Loss=1.0977216958999634 LR=0.0173300981595092 Batch_id=97 Accuracy=55.13: 100%|██████████| 98/98 [00:41<00:00,  2.35it/s]

Test set: Average loss: 0.0030, Accuracy: 5289/10000 (52.89%)

EPOCH: 2
Loss=1.0748182535171509 LR=0.025782147239263798 Batch_id=97 Accuracy=62.41: 100%|██████████| 98/98 [00:41<00:00,  2.35it/s]

Test set: Average loss: 0.0032, Accuracy: 5163/10000 (51.63%)

EPOCH: 3
Loss=0.9508823156356812 LR=0.0342341963190184 Batch_id=97 Accuracy=66.32: 100%|██████████| 98/98 [00:41<00:00,  2.36it/s]

Test set: Average loss: 0.0025, Accuracy: 5840/10000 (58.40%)

EPOCH: 4
Loss=1.027746558189392 LR=0.042571023306122446 Batch_id=97 Accuracy=66.85: 100%|██████████| 98/98 [00:41<00:00,  2.36it/s]

Test set: Average loss: 0.0037, Accuracy: 4161/10000 (41.61%)

EPOCH: 5
Loss=0.8966213464736938 LR=0.03973130730612245 Batch_id=97 Accuracy=68.18: 100%|██████████| 98/98 [00:41<00:00,  2.37it/s]

Test set: Average loss: 0.0030, Accuracy: 5371/10000 (53.71%)

EPOCH: 6
Loss=0.9200765490531921 LR=0.03689159130612245 Batch_id=97 Accuracy=69.86: 100%|██████████| 98/98 [00:41<00:00,  2.37it/s]

Test set: Average loss: 0.0029, Accuracy: 5747/10000 (57.47%)

EPOCH: 7
Loss=0.857201099395752 LR=0.03405187530612245 Batch_id=97 Accuracy=70.86: 100%|██████████| 98/98 [00:41<00:00,  2.39it/s]

Test set: Average loss: 0.0024, Accuracy: 5947/10000 (59.47%)

EPOCH: 8
Loss=0.8627192378044128 LR=0.03121215930612245 Batch_id=97 Accuracy=72.79: 100%|██████████| 98/98 [00:41<00:00,  2.38it/s]

Test set: Average loss: 0.0022, Accuracy: 6230/10000 (62.30%)

EPOCH: 9
Loss=0.8284728527069092 LR=0.028372443306122447 Batch_id=97 Accuracy=73.25: 100%|██████████| 98/98 [00:40<00:00,  2.39it/s]

Test set: Average loss: 0.0016, Accuracy: 7312/10000 (73.12%)

EPOCH: 10
Loss=0.7379891276359558 LR=0.02553272730612245 Batch_id=97 Accuracy=74.69: 100%|██████████| 98/98 [00:40<00:00,  2.39it/s]

Test set: Average loss: 0.0040, Accuracy: 5363/10000 (53.63%)

EPOCH: 11
Loss=0.697508692741394 LR=0.02269301130612245 Batch_id=97 Accuracy=75.72: 100%|██████████| 98/98 [00:40<00:00,  2.39it/s]

Test set: Average loss: 0.0018, Accuracy: 7046/10000 (70.46%)

EPOCH: 12
Loss=0.7620857954025269 LR=0.019853295306122447 Batch_id=97 Accuracy=76.25: 100%|██████████| 98/98 [00:40<00:00,  2.40it/s]

Test set: Average loss: 0.0022, Accuracy: 6384/10000 (63.84%)

EPOCH: 13
Loss=0.5996698141098022 LR=0.017013579306122448 Batch_id=97 Accuracy=78.00: 100%|██████████| 98/98 [00:40<00:00,  2.40it/s]

Test set: Average loss: 0.0016, Accuracy: 7250/10000 (72.50%)

EPOCH: 14
Loss=0.5392720103263855 LR=0.014173863306122449 Batch_id=97 Accuracy=79.38: 100%|██████████| 98/98 [00:40<00:00,  2.40it/s]

Test set: Average loss: 0.0016, Accuracy: 7289/10000 (72.89%)

EPOCH: 15
Loss=0.5538424253463745 LR=0.01133414730612245 Batch_id=97 Accuracy=80.83: 100%|██████████| 98/98 [00:40<00:00,  2.40it/s]

Test set: Average loss: 0.0012, Accuracy: 8006/10000 (80.06%)

EPOCH: 16
Loss=0.6195296049118042 LR=0.00849443130612245 Batch_id=97 Accuracy=82.43: 100%|██████████| 98/98 [00:40<00:00,  2.41it/s]

Test set: Average loss: 0.0011, Accuracy: 8086/10000 (80.86%)

EPOCH: 17
Loss=0.544552206993103 LR=0.0056547153061224514 Batch_id=97 Accuracy=84.99: 100%|██████████| 98/98 [00:40<00:00,  2.41it/s]

Test set: Average loss: 0.0010, Accuracy: 8395/10000 (83.95%)

EPOCH: 18
Loss=0.3389090597629547 LR=0.0028149993061224524 Batch_id=97 Accuracy=87.38: 100%|██████████| 98/98 [00:40<00:00,  2.40it/s]

Test set: Average loss: 0.0008, Accuracy: 8605/10000 (86.05%)

EPOCH: 19
Loss=0.269216388463974 LR=-2.4716693877546714e-05 Batch_id=97 Accuracy=90.67: 100%|██████████| 98/98 [00:40<00:00,  2.41it/s]

Test set: Average loss: 0.0007, Accuracy: 8813/10000 (88.13%)

## Misclassified Images : 

![image](https://github.com/sunandhini96/ERA_S11/assets/63030539/45311320-29c9-405b-92dd-68c5658aff4f)

## Gradcam (correctly classified):

![image](https://github.com/sunandhini96/ERA_S11/assets/63030539/e3d638de-fad6-47a2-b30b-b00f2752795c)

## Gradcam (misclassified ):

![image](https://github.com/sunandhini96/ERA_S11/assets/63030539/64ef09e8-4274-4476-bbb3-27b6c8551817)






