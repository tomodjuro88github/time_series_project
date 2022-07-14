# time_series_project

Time series forecasting is a technique for predicting events through a time sequence. The technique is used in many fields of study, from geology to behaviour to economics. Techniques predict future events by analyzing trends from the past, assuming that future trends will hold similar to historical trends.

In this project I wanted to predict stock price with Prophet model and predict weather data (temperature and pressure) with LSTM and CNN. First part is a traditional approach with using Facebook’s Prophet model and second part is a machine learning approach using neural networks (LSTM,CNN).

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data.

LSTM stands for Short Term Long Term Memory. It is a model or an architecture that extends the memory of recurrent neural networks. Typically, recurrent neural networks have “short-term memory” in that they use persistent past information for use in the current neural network. Essentially, the previous information is used in the current task. This means that we do not have a list of all of the previous information available for the neural node.

CNN stands for Convolutional neural network. CNNs have their roots in image processing. It was first published in LeNet to recognize the MNIST handwritten digits. However, convolutional neural networks are not limited to handling images. As mentioned, CNNs’s convolutions are popularly known to work on spatial or 2D data. What’s less popular is that there are also convolutions for 1D data. This allows CNN to be used in more general data type including texts and other time series data. Instead of extracting spatial information, you use 1D convolutions to extract information along the time dimension.
