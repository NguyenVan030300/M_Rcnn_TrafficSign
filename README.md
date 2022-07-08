# M_Rcnn_TrafficSign
---
# Step 1: Clone and Install Requirements

Make sure to check if Keras version is 2.2.5 and tensorflow version 1.x using this code, if it's not keras version 2.2.5 run all the !pip installation again and restart runtime till you get the correct keras version

%tensorflow_version 1.x

import tensorflow

import keras

print(keras.version)

![image](https://user-images.githubusercontent.com/100404612/177893529-47edb810-7bc9-4f03-80c4-c2708d9b4c11.png)

![tải xuống](https://user-images.githubusercontent.com/100404612/177893570-df293fb2-cfc3-4a16-9726-d9fa3351bd62.png)

After the code tell that you have the right Keras and Tensorflow version go to step 2

![image](https://user-images.githubusercontent.com/100404612/177893646-2d383a57-1b64-4791-a353-fde72459dcb1.png)

---
# Step 2: Custom config for your dataset to train

I already config for this TrafficSign dataset for you to go straight to Training

![image](https://user-images.githubusercontent.com/100404612/177893755-0ef016f4-ea35-4d0f-b3be-583a3996357d.png)

The only thing is to make sure the dataset path is correct for this cell

![image](https://user-images.githubusercontent.com/100404612/177893852-e49b31e0-e1ef-4e91-b787-2365f1d7b716.png)

---
# Step 3: Training

Run the two cell for training, in this case i also using coco pretrain weight for training.

![image](https://user-images.githubusercontent.com/100404612/177893980-92713706-dea6-4fc9-8b0a-be4af2fc6586.png)

---
# Step 4: Testing and Evaluate

You can use my already train on 27 epoch for bien_bao dataset to predict

![tải xuống (1)](https://user-images.githubusercontent.com/100404612/177894183-ba783658-5255-4fa0-bda3-3a72d8fb9bcf.png)

Loading the Val dataset

![image](https://user-images.githubusercontent.com/100404612/177894371-725101f5-c5ea-4c4c-a8ed-ad1aac16e7fb.png)

Run the config2 for Testing

![image](https://user-images.githubusercontent.com/100404612/177894406-cbdd84c5-1e1c-433a-a678-4870bcc350a1.png)

Code for runing random image in val dataset to get the prediction

![image](https://user-images.githubusercontent.com/100404612/177894523-f8afd916-aeaf-43b8-a1cf-b05ee8fac76b.png)

Code to Evaluate the dataset in this case the Val

![image](https://user-images.githubusercontent.com/100404612/177894541-9330300b-6b7d-46a3-a2cb-3691e75766ee.png)
