# CNN-based-non-linear-regression

use 1d CNN model to train the non-linear function : y = x^2 + 6x + 9
- input x.shape:[1000, 1, 300]
- output y.shape:[1000, 1, 300]
- CNN model:
  - conv1d:(k_size=(300), stride=1, padding=148)
  - ReLU
  - conv1d:(k_size=(300), stride=1, padding=149)
  - ReLU
