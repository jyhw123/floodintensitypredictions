# surfacewaterhydrology
**Comparisonal investigation of Classic vs Deep Learning models in predicting flood intensity in the CONUS**

The study of hydrology has allowed scientists to better understand the natural distribution and movement of water, as well as its interactions with our environment. Due to constant changes in the environment and weather, we are unable to fully comprehend the entire cycle, and hence this leads to high uncertainty in the predictions of future water patterns. 

Drainage basins, otherwise known as watersheds, are areas that drain streams and rainfall/snowfall to a common outlet such as the outflow of a reservoir, mouth of a bay, or any point along a stream channel. It is vital to understand the processes of a basin, as it protects the water quality, and is directly and indirectly beneficial to mankind, providing us with a clean source of water.

This project aims to create hydrological models to predict the streamflow rate of a basin using relevant physical factors. The Catchment Attributes and Meteorology for Large-sample Studies (CAMELS) community dataset will be used to provide basin data in the United States of America.

For this project, we decided to use 2 classes of Machine Learning models: Classical models and Deep Learning Models. Under the Classical models tier, we chose the SARIMAX Model and the XGBoost model, and chose the LSTM and Prophet Model for the Deep Learning tier. Classical models and Deep Learning models each have their benefits and drawbacks, which is why it is important to implement both tiers. Classical models, amongst many other things, benefit from shorter training time and less data required, whilst Deep Learning models might produce better performing predictions if configured properly.  

