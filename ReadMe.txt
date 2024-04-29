Files structure:
1. Mqttfinal.ipynb (jupyter notebook)- to be run all code in file to begin mqtt server and publish data. Also, ensure that the file paths are correct to the file:(testdata.csv,StandardScaler.pkl,LSTMModel_95.5.h5,)
2. ML_LSTM.ipynb (jupyter notebook)- contains all the source code to build and train the LSTM model for predictions. Ensure the path to input dataset file:(rainfall.csv). Caution: To be run only when need to retrain or build new model.
3. flowsfinal.json (node-red flow)- consists the flow data to simulate the environment in node-red

Requirements:
1. python3
2. node-red
3. Mosquitto server framework
4. node.js

To run the complete project just need to run two files:
1. Mqttfinal.ipynb (jupyter notebook)
2. flowsfinal.json (node-red)