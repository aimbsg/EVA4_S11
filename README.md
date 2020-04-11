# EVA4_S11
One cycle policy on CIFAR10
Train accuracy - 96.5% ; Validation accuracy - 90.4% ; Epochs = 24
Best LR : 0.007196856730011518 (from LR range test)
Max LR : 0.01 ; Min LR = 0.001

Model summary :
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1           [-1, 64, 32, 32]           1,728
       BatchNorm2d-2           [-1, 64, 32, 32]             128
              ReLU-3           [-1, 64, 32, 32]               0
            Conv2d-4          [-1, 128, 32, 32]          73,728
         MaxPool2d-5          [-1, 128, 16, 16]               0
       BatchNorm2d-6          [-1, 128, 16, 16]             256
              ReLU-7          [-1, 128, 16, 16]               0
            Conv2d-8          [-1, 128, 16, 16]         147,456
       BatchNorm2d-9          [-1, 128, 16, 16]             256
             ReLU-10          [-1, 128, 16, 16]               0
           Conv2d-11          [-1, 128, 16, 16]         147,456
      BatchNorm2d-12          [-1, 128, 16, 16]             256
             ReLU-13          [-1, 128, 16, 16]               0
           Conv2d-14          [-1, 256, 16, 16]         294,912
        MaxPool2d-15            [-1, 256, 8, 8]               0
      BatchNorm2d-16            [-1, 256, 8, 8]             512
             ReLU-17            [-1, 256, 8, 8]               0
           Conv2d-18            [-1, 512, 8, 8]       1,179,648
        MaxPool2d-19            [-1, 512, 4, 4]               0
      BatchNorm2d-20            [-1, 512, 4, 4]           1,024
             ReLU-21            [-1, 512, 4, 4]               0
           Conv2d-22            [-1, 512, 4, 4]       2,359,296
      BatchNorm2d-23            [-1, 512, 4, 4]           1,024
             ReLU-24            [-1, 512, 4, 4]               0
           Conv2d-25            [-1, 512, 4, 4]       2,359,296
      BatchNorm2d-26            [-1, 512, 4, 4]           1,024
             ReLU-27            [-1, 512, 4, 4]               0
        MaxPool2d-28            [-1, 512, 1, 1]               0
           Linear-29                   [-1, 10]           5,120
================================================================
Total params: 6,573,120
Trainable params: 6,573,120
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 6.44
Params size (MB): 25.07
Estimated Total Size (MB): 31.53
----------------------------------------------------------------

Model log :
  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 1 LR: 0.001
Loss=1.351626992225647 Batch_id=97 Accuracy=39.28: 100%|██████████| 98/98 [00:21<00:00,  4.57it/s]

Test set: Average loss: 0.0027, Accuracy: 5181/10000 (51.81%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 2 LR: 0.002046511627906977
Loss=1.0715376138687134 Batch_id=97 Accuracy=56.22: 100%|██████████| 98/98 [00:20<00:00,  4.67it/s]

Test set: Average loss: 0.0022, Accuracy: 6133/10000 (61.33%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 3 LR: 0.0030930232558139537
Loss=0.9967455267906189 Batch_id=97 Accuracy=64.40: 100%|██████████| 98/98 [00:21<00:00,  4.56it/s]

Test set: Average loss: 0.0019, Accuracy: 6594/10000 (65.94%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 4 LR: 0.00413953488372093
Loss=0.6832113265991211 Batch_id=97 Accuracy=70.66: 100%|██████████| 98/98 [00:21<00:00,  4.48it/s]

Test set: Average loss: 0.0016, Accuracy: 7257/10000 (72.57%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 5 LR: 0.005186046511627907
Loss=0.6586498618125916 Batch_id=97 Accuracy=74.41: 100%|██████████| 98/98 [00:21<00:00,  4.60it/s]

Test set: Average loss: 0.0015, Accuracy: 7394/10000 (73.94%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 6 LR: 0.006232558139534884
Loss=0.5309688448905945 Batch_id=97 Accuracy=77.71: 100%|██████████| 98/98 [00:21<00:00,  4.58it/s]

Test set: Average loss: 0.0013, Accuracy: 7688/10000 (76.88%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 7 LR: 0.00727906976744186
Loss=0.42416414618492126 Batch_id=97 Accuracy=80.20: 100%|██████████| 98/98 [00:21<00:00,  4.55it/s]

Test set: Average loss: 0.0013, Accuracy: 7809/10000 (78.09%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 8 LR: 0.008325581395348837
Loss=0.5729008316993713 Batch_id=97 Accuracy=82.22: 100%|██████████| 98/98 [00:21<00:00,  4.61it/s]

Test set: Average loss: 0.0016, Accuracy: 7349/10000 (73.49%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 9 LR: 0.009372093023255815
Loss=0.4468766748905182 Batch_id=97 Accuracy=83.61: 100%|██████████| 98/98 [00:21<00:00,  4.58it/s]

Test set: Average loss: 0.0011, Accuracy: 8172/10000 (81.72%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 10 LR: 0.00990625
Loss=0.38029202818870544 Batch_id=97 Accuracy=85.54: 100%|██████████| 98/98 [00:21<00:00,  4.56it/s]

Test set: Average loss: 0.0010, Accuracy: 8183/10000 (81.83%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 11 LR: 0.009671875
Loss=0.42573466897010803 Batch_id=97 Accuracy=87.37: 100%|██████████| 98/98 [00:21<00:00,  4.57it/s]

Test set: Average loss: 0.0010, Accuracy: 8385/10000 (83.85%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 12 LR: 0.0094375
Loss=0.28190386295318604 Batch_id=97 Accuracy=88.52: 100%|██████████| 98/98 [00:21<00:00,  4.64it/s]

Test set: Average loss: 0.0009, Accuracy: 8552/10000 (85.52%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 13 LR: 0.009203125000000001
Loss=0.3390583097934723 Batch_id=97 Accuracy=89.94: 100%|██████████| 98/98 [00:21<00:00,  4.60it/s]

Test set: Average loss: 0.0009, Accuracy: 8560/10000 (85.60%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 14 LR: 0.008968750000000001
Loss=0.260982871055603 Batch_id=97 Accuracy=90.89: 100%|██████████| 98/98 [00:21<00:00,  4.62it/s]

Test set: Average loss: 0.0008, Accuracy: 8701/10000 (87.01%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 15 LR: 0.008734375
Loss=0.2516319155693054 Batch_id=97 Accuracy=91.39: 100%|██████████| 98/98 [00:21<00:00,  4.50it/s]

Test set: Average loss: 0.0009, Accuracy: 8538/10000 (85.38%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 16 LR: 0.0085
Loss=0.20998550951480865 Batch_id=97 Accuracy=92.17: 100%|██████████| 98/98 [00:21<00:00,  4.50it/s]

Test set: Average loss: 0.0007, Accuracy: 8776/10000 (87.76%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 17 LR: 0.008265625
Loss=0.18043658137321472 Batch_id=97 Accuracy=93.14: 100%|██████████| 98/98 [00:21<00:00,  4.57it/s]

Test set: Average loss: 0.0009, Accuracy: 8532/10000 (85.32%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 18 LR: 0.00803125
Loss=0.136215478181839 Batch_id=97 Accuracy=93.81: 100%|██████████| 98/98 [00:21<00:00,  4.50it/s]

Test set: Average loss: 0.0008, Accuracy: 8752/10000 (87.52%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 19 LR: 0.007796875
Loss=0.16311132907867432 Batch_id=97 Accuracy=94.25: 100%|██████████| 98/98 [00:21<00:00,  4.61it/s]

Test set: Average loss: 0.0007, Accuracy: 8811/10000 (88.11%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 20 LR: 0.0075625
Loss=0.1936977505683899 Batch_id=97 Accuracy=95.01: 100%|██████████| 98/98 [00:21<00:00,  4.56it/s]

Test set: Average loss: 0.0007, Accuracy: 8887/10000 (88.87%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 21 LR: 0.007328125
Loss=0.13565696775913239 Batch_id=97 Accuracy=95.48: 100%|██████████| 98/98 [00:21<00:00,  4.49it/s]

Test set: Average loss: 0.0007, Accuracy: 8849/10000 (88.49%)

  0%|          | 0/98 [00:00<?, ?it/s]Epoch: 22 LR: 0.00709375
Loss=0.13118602335453033 Batch_id=97 Accuracy=95.79: 100%|██████████| 98/98 [00:21<00:00,  4.59it/s]

Test set: Average loss: 0.0007, Accuracy: 8933/10000 (89.33%)

...BEST MODEL...
  0%|          | 0/98 [00:00<?, ?it/s]Save success...
Epoch: 23 LR: 0.006859375
Loss=0.18141035735607147 Batch_id=97 Accuracy=96.15: 100%|██████████| 98/98 [00:21<00:00,  4.48it/s]

Test set: Average loss: 0.0006, Accuracy: 8951/10000 (89.51%)

  0%|          | 0/98 [00:00<?, ?it/s]...BEST MODEL...
Save success...
Epoch: 24 LR: 0.006625
Loss=0.15807849168777466 Batch_id=97 Accuracy=96.50: 100%|██████████| 98/98 [00:21<00:00,  4.50it/s]

Test set: Average loss: 0.0006, Accuracy: 9040/10000 (90.40%)

...BEST MODEL...
Save success...

Class accuracy :
Accuracy of plane : 91 %
Accuracy of   car : 96 %
Accuracy of  bird : 84 %
Accuracy of   cat : 84 %
Accuracy of  deer : 89 %
Accuracy of   dog : 81 %
Accuracy of  frog : 92 %
Accuracy of horse : 96 %
Accuracy of  ship : 96 %
Accuracy of truck : 91 %
