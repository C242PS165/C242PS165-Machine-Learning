# C242PS165-Machine-Learning
# SmartFarm Model

## Dataset Source
Dataset source: (https://www.kaggle.com/datasets/greegtitan/indonesia-climate)


## Model Description:
- Cleaning the data (including dropping unused columns, and removing duplicate data)
- Preprocessing (including one-hot encoding)
- Building the model using TensorFlow time series dan LSTM
- Recommendation output with value of model prediction result

All the steps bellow based on: https://www.tensorflow.org/tutorials/structured_data/time_series?hl=id


## Model SmartFarm Source Code
This model was built by using a collaborative filtering method and the model code documentation is below:
[SmartFarm Source Code](https://github.com/C242PS165/C242PS165-Machine-Learning/blob/85c1959f52b6f0886aeb373dae14162b2016b359/SmartFarm-climate.ipynb) 


## Exported Model File
This model was saved:
- using tfjs tf.saved_model() at [SmartFarm_model_tfjs](https://github.com/C242PS165/C242PS165-Machine-Learning/tree/85c1959f52b6f0886aeb373dae14162b2016b359/SmartFarm_model_tfjs)
- and using terminal !tensorflowjs_converter --input_format=tf_saved_model --output_format=tfjs_graph_model model_tfjs ./export_tfjs/ (tensorflowjs converter) [SmartFarm_model_tfjs](https://github.com/C242PS165/C242PS165-Machine-Learning/tree/85c1959f52b6f0886aeb373dae14162b2016b359/SmartFarm_model_tfjs)
- using H5 tf.saved_model() at [SmartFarm_model_tfjs](https://github.com/C242PS165/C242PS165-Machine-Learning/blob/4973fe0325d0c89c2efb081a8a32ceb06c96d3dd/SmartFarm_model_H5/smartfarm_model.h5)
- and using terminal lstm_model.save('smartfarm_model.h5') (tensorflow h5 save model) [SmartFarm h5](https://github.com/C242PS165/C242PS165-Machine-Learning/tree/4973fe0325d0c89c2efb081a8a32ceb06c96d3dd/SmartFarm_model_H5)
