First try:
    Layers:
        1. Conv2D  (32 filters, 3x3 kernel, activation = relu)
        2. Flatten
        3. Dense
    Results:
        Loss: 1.1722
        Accuracy: 0.9058
        Duration: 4-5 secs per epoch

Second try:
    Layers:
        1. Conv2D  (32 filters, 3x3 kernel, activation = relu)
        2. Dropout (rate 0.2)
        3. Flatten
        4. Dense
    Results:
        Loss: 0.9553
        Accuracy: 0.9011
        Duration: 8 secs per epoch

Third Try:
    Layers:
        1. Conv2D  (32 filters, 3x3 kernel, activation = relu)
        2. MaxPooling2D ((2,2) pool size)
        3. Flatten
        4. Dense
    Results:
        Loss: 1.1865
        Accuracy: 0.8988
        Duration: 4 secs per epoch

Fourth Try:
    Layers:
        1. Conv2D  (32 filters, 3x3 kernel, activation = relu)
        2. MaxPooling2D ((2,2) pool size)
        3. Dropout(0.2)
        4. Flatten
        5. Dense
    Results:
        Loss: 0.7041
        Accuracy: 0.9378
        Duration: 4 secs per epoch

Fifth Try:
    Layers:
        1. Conv2D  (32 filters, 4x4 kernel, activation = relu)
        2. MaxPooling2D ((2,2) pool size)
        3. Dropout(0.2)
        4. Flatten
        5. Dense
    Results:
        Loss: 0.7098
        Accuracy: 0.9118
        Duration: 4 secs per epoch

Sixth Try:
    Layers:
        1. Conv2D  (32 filters, 3x3 kernel, activation = relu)
        2. MaxPooling2D ((2,2) pool size)
        3. Dropout(0.5)
        4. Flatten
        5. Dense
    Results:
        Loss: 0.5512
        Accuracy: 0.8971
        Duration: 4 secs per epoch
    
Seventh Try:
    Layers:
        1. Conv2D  (32 filters, 3x3 kernel, activation = relu)
        2. MaxPooling2D ((3,3) pool size)
        3. Dropout(0.2)
        4. Flatten
        5. Dense
    Results:
        Loss: 0.5439
        Accuracy: 0.9079
        Duration: 4 secs per epoch