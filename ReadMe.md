Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 10s 172us/step - loss: 0.7471 - acc: 0.7514 - val_loss: 0.1196 - val_acc: 0.9761
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 6s 103us/step - loss: 0.4225 - acc: 0.8479 - val_loss: 0.0685 - val_acc: 0.9854
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 6s 104us/step - loss: 0.3530 - acc: 0.8648 - val_loss: 0.0564 - val_acc: 0.9860
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 6s 103us/step - loss: 0.3172 - acc: 0.8712 - val_loss: 0.0400 - val_acc: 0.9906
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 6s 103us/step - loss: 0.3024 - acc: 0.8720 - val_loss: 0.0377 - val_acc: 0.9898
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 6s 105us/step - loss: 0.2876 - acc: 0.8745 - val_loss: 0.0327 - val_acc: 0.9913
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 6s 106us/step - loss: 0.2805 - acc: 0.8740 - val_loss: 0.0285 - val_acc: 0.9920
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 6s 103us/step - loss: 0.2758 - acc: 0.8736 - val_loss: 0.0298 - val_acc: 0.9920
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 6s 103us/step - loss: 0.2652 - acc: 0.8758 - val_loss: 0.0311 - val_acc: 0.9905
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 6s 103us/step - loss: 0.2636 - acc: 0.8758 - val_loss: 0.0284 - val_acc: 0.9920
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 6s 102us/step - loss: 0.2577 - acc: 0.8773 - val_loss: 0.0238 - val_acc: 0.9943
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 6s 102us/step - loss: 0.2560 - acc: 0.8780 - val_loss: 0.0260 - val_acc: 0.9921
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 6s 103us/step - loss: 0.2558 - acc: 0.8759 - val_loss: 0.0231 - val_acc: 0.9932
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 6s 102us/step - loss: 0.2508 - acc: 0.8797 - val_loss: 0.0253 - val_acc: 0.9923
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 6s 103us/step - loss: 0.2489 - acc: 0.8779 - val_loss: 0.0226 - val_acc: 0.9934
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 6s 104us/step - loss: 0.2452 - acc: 0.8818 - val_loss: 0.0205 - val_acc: 0.9944
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 6s 103us/step - loss: 0.2443 - acc: 0.8801 - val_loss: 0.0206 - val_acc: 0.9937
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 6s 103us/step - loss: 0.2469 - acc: 0.8783 - val_loss: 0.0204 - val_acc: 0.9945
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 6s 103us/step - loss: 0.2414 - acc: 0.8793 - val_loss: 0.0207 - val_acc: 0.9938
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 6s 102us/step - loss: 0.2404 - acc: 0.8798 - val_loss: 0.0200 - val_acc: 0.9941
<keras.callbacks.History at 0x7fde45d520b8>


Strategy was to reduce the number of parameters in the first parameter and kept dropout value to 0.2 to reduce the val_loss and got the accuracy of 99.43 at 11th epoch
