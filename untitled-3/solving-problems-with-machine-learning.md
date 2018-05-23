# Solving Problems with Machine Learning

## Approaching Problems

When you have a problem that you want to use Machine Learning to solve, you will need a dataset and break down what the problem is. Breaking down the problem can be down by asking some questions  like "How many features?" or "Are you trying to predict something?". After answering these questions, you can choose the correct type of algorithm to use on the dataset in order to try to get a meaningful result. 

In this section, we will look at resources that will help you decide what algorithm to use and tools that can help you implement a solution.

## Choosing An Algorithm

### Microsoft Azure ML

The first thing is choosing an algorithm. Below is a cheat sheet that contains all algorithms that are currently supported by Microsoft Azure ML and this can be used to help decide on an algorithm. Depending on what kind of problem you are solving, the cheat sheet will lead you to a type of Machine Learning algorithm and what specific algorithm that would be the best fit. 

![](../.gitbook/assets/image%20%281%29.png)

A breakdown of this cheat sheet can be found [here](https://docs.microsoft.com/en-us/azure/machine-learning/studio/algorithm-cheat-sheet). If you want a more advanced breakdown that goes into detail about the algorithms on the cheat sheet, go [here](https://docs.microsoft.com/en-us/azure/machine-learning/studio/algorithm-choice).

Another resource is the infographic that is found [here](https://docs.microsoft.com/en-us/azure/machine-learning/studio/basics-infographic-with-algorithm-examples). This has a different layout and flow than the one above.

### Scikit-learn

Scikit-learn is another resource for choosing algorithms and has the following cheat sheet.

![](../.gitbook/assets/image%20%282%29.png)

An interactive version of this can be found [here](http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html) and goes into each one in more depth.

## List of Tools and Frameworks

The following is a list of tools and frameworks that can be used:

* [Jupyter](http://jupyter.org/) - Open source web application for sharing notebooks 
* [scikit-learn](http://scikit-learn.org/stable/documentation.html) - Machine learning in Python tool
* [Azure ML](https://studio.azureml.net/) - Browser-base machine learning environment
* [Microsoft Cognitive Toolkit \(CNTK\)](https://github.com/Microsoft/CNTK) -  A Microsoft open source deep-learning toolkit 
* [Accord.NET](http://accord-framework.net/) -  a .NET machine learning framework combined with audio and image processing libraries completely written in C\#

Some more advanced tools and networks:

* [Keras](https://keras.io/) - High-level neural networks API
* [TensorFlow](https://www.tensorflow.org/) - Open source library for high performance numerical computation
* [Torch](http://torch.ch/) - Scientific computing framework for machine learning

## Examples

### Microsoft Azure ML

Azure Machine Learning Studio has a [gallery](https://gallery.azure.ai/) that contains many examples that you can import into your Azure workspace to view, modify, and run. The following link are some examples:

{% embed data="{\"url\":\"https://gallery.azure.ai/Tutorial/Customer-Churn-and-Real-time-Analytics\",\"type\":\"link\",\"title\":\"Customer Churn and Real-time Analytics\",\"description\":\"In today\'s fast-paced world, mobile phone customers have many choices and can easily switch between service providers. Many industries, including mobile providers, use Churn Models to predict which customers are most likely to leave, and to understand which factors cause customers to stop using their service. This solution shows you how to build a real-life churn model with Azure Machine Learning, make it enterprise-ready with Azure Data Factory, and deliver data insights with Power BI. You will also see how to collect real-time Call Details Records \(CDRs\), and use that to deliver analytical results with Power BI Tags: Solution, Azure Data Factory, Azure Sql, Azure Blob Storage, Azure Machine Learning, PowerBI\",\"icon\":{\"type\":\"icon\",\"url\":\"https://gallery.azure.ai/images/favicon\_bundle.ico\",\"aspectRatio\":0},\"thumbnail\":{\"type\":\"thumbnail\",\"url\":\"https://caqsres.blob.core.windows.net/telcocustomerchurnv2/TelcoCustomerChurn.jpg\",\"width\":960,\"height\":640,\"aspectRatio\":0.6666666666666666}}" %}



{% embed data="{\"url\":\"https://gallery.azure.ai/MachineLearningAPI/Anomaly-Detection-2\",\"type\":\"link\",\"title\":\"Anomaly Detection\",\"description\":\"Detect different anomalous patterns in your time series data using machine learning algorithms. Level changes, trend changes, spikes are supported on seasonal and non-seasonal time series. Tags: Anomaly, Time series, IoT\",\"icon\":{\"type\":\"icon\",\"url\":\"https://gallery.azure.ai/images/favicon\_bundle.ico\",\"aspectRatio\":0},\"thumbnail\":{\"type\":\"thumbnail\",\"url\":\"https://az712634.vo.msecnd.net/content/14b2744cf8d6418c87ffddc3f3127242/9502630827244d60a1214f250e3bbca7/6ff944cff52a47daa7dfe7bfe7fdb442/141056043d5141e5ad3023ab065c3444/image\",\"width\":570,\"height\":380,\"aspectRatio\":0.6666666666666666}}" %}

### Scikit-learn

 Scikit-learn has various [examples](http://scikit-learn.org/stable/auto_examples/index.html) available that contains code to run and explanations of the example. The following are some examples:

{% embed data="{\"url\":\"http://scikit-learn.org/stable/auto\_examples/applications/plot\_outlier\_detection\_housing.html\#sphx-glr-auto-examples-applications-plot-outlier-detection-housing-py\",\"type\":\"link\",\"title\":\"Outlier detection on a real data set — scikit-learn 0.19.1 documentation\",\"icon\":{\"type\":\"icon\",\"url\":\"http://scikit-learn.org/stable/\_static/favicon.ico\",\"aspectRatio\":0}}" %}



{% embed data="{\"url\":\"http://scikit-learn.org/stable/auto\_examples/applications/plot\_stock\_market.html\#sphx-glr-auto-examples-applications-plot-stock-market-py\",\"type\":\"link\",\"title\":\"Visualizing the stock market structure — scikit-learn 0.19.1 documentation\",\"icon\":{\"type\":\"icon\",\"url\":\"http://scikit-learn.org/stable/\_static/favicon.ico\",\"aspectRatio\":0}}" %}



