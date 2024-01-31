# Time-series-forecasting-using-TimeGPT

![image](https://github.com/FeresDarouich/Time-series-forecasting-using-TimeGPT/assets/120333973/96075e17-2475-4bc6-96ee-d9e194e1cc53)

the general idea behind TimeGPT is to train a model on massive amounts of data from different domains to then produce zero-shot inference on unseen data and this method relies on transfer learning, which is the capacity of a model to solve a new task using its knowledge gained during training. this only works if the model is large enough, and if it is trained on lots of data. 

TimeGPT is trained on more than 100 billion data points all coming from open-source time series data. The dataset spans a wide array of domains, from finance, economics and weather, to web traffic, energy and sales.This variety is critical for the success of a foundation model, as it can learn different temporal patterns and therefore generalize better.


![image](https://github.com/FeresDarouich/Time-series-forecasting-using-TimeGPT/assets/120333973/c62a6f94-32c8-4d3d-908d-db2fa0cf3296)


TimeGPT uses the full encoder-decoder Transformer architecture.The inputs can consist of a window of historical data, as well as exogenous data, like punctual events or another series. 

The inputs are fed to the encoder portion of the model. The attention mechanism inside the encoder then learns different properties from the inputs. This is then fed to the decoder, which uses the learned information to produce forecasts.
