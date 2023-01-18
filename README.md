**Project Portfolio: https://github.com/calebyhan/CalebHan**

Uses Convoluted Neural Networks (CNN) to recognize various functions such as circles, ellipses, parabolas, and linear functions.

<details>
  <summary>Layers</summary>
  
  ```
  Model: "sequential1"
  _________________________________________________________________
   Layer (type)                Output Shape              Param #
  =================================================================
   conv2d_3 (Conv2D)           (None, 224, 224, 32)      896

   max_pooling2d_3 (MaxPooling  (None, 112, 112, 32)     0
   2D)

   conv2d_4 (Conv2D)           (None, 112, 112, 32)      9248

   max_pooling2d_4 (MaxPooling  (None, 56, 56, 32)       0
   2D)

   conv2d_5 (Conv2D)           (None, 56, 56, 64)        18496

   max_pooling2d_5 (MaxPooling  (None, 28, 28, 64)       0
   2D)

   dropout_1 (Dropout)         (None, 28, 28, 64)        0

   flatten_1 (Flatten)         (None, 50176)             0

   dense_2 (Dense)             (None, 128)               6422656

   dense3 (Dense)             (None, 7)                 903

  =================================================================
  Total params: 6,452,199
  Trainable params: 6,452,199
  Non-trainable params: 0
  _________________________________________________________________
  ```

</details>

<details><summary>Epochs</summary>

</details>
