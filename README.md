
# StockMarket Prediction Web App
This is official repository of stockmarket prediction web App
using Long Short-Term Memory (LSTM) is a type of recurrent neural network (RNN) Model
Official deployment:https://stockmarketai-predict-akshat.onrender.com/




## Output
Infosys Stock detail as listed in Nasdaq Usa data taking from library of yahoo yfinance
![Screenshot 2024-02-09 003201](https://github.com/akshats1/StockMarket_AI/assets/6964294/4d86906d-000c-4a08-bf90-5ebfeefd8f18)

Prices according Moving Average 50
![Screenshot 2024-02-09 005746](https://github.com/akshats1/StockMarket_AI/assets/6964294/fb84f9ee-11cf-412e-9c2b-0448293b7901)

Prices according Moving Average 50 and Moving Average 100
![Screenshot 2024-02-09 005759](https://github.com/akshats1/StockMarket_AI/assets/6964294/aa7ddd4d-93ae-4718-a5a4-28faf3f8ce46)


Prediction of stock price as per Our Model
![image](https://github.com/akshats1/StockMarket_AI/assets/6964294/140e7567-8a73-44e3-b28b-e42085a9a1d9)




## Demo

https://stockmarketai-predict-akshat.onrender.com/
Docker Demo:https://hub.docker.com/r/akshats063/shareprice
      Docker pull request
      docker pull akshats063/shareprice
## How to Run
```bash
conda create -n visa python=3.8 -y
```
```bash
conda activate visa
```
```bash
pip install -r requirements.txt
```

```bash
python3 app.py

```

## Tech Stack

**Client:** Python, Keras,Tensorflow,LSTM,yifinance,streamlit

**Server:** streamlit,render.com

## Deployment

To deploy this project run


```bash
  streamlit run app.py
```
```bash
  pip install -r requirements.txt
```




