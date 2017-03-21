# IoT-Storage-StreamAnalytics-Function-MTC
ARM template

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fyogsgit%2FARM-Templates%2Fmaster%2FIoT-Storage-StreamAnalytics-Function-MTC%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-streamanalytics-create%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template is a part of the blog [Processing MTConnect data using Azure IoT hub, Stream Analytics, Azure Functions and Power BI live reports](https://codedesignetc.com/2017/03/21/processing-mtconnect-data-using-azure-iot-hub-stream-analytics-azure-functions-power-bi-streaming-datasets/)

This ARM template creates following Azure resources:
- IoT Hub
- Storage Account
- Service Bus Namespace with 1 Queue
- Function App
- Stream Analytics Job

MTConnect is a protocol designed for the exchange of data between shop floor equipment and software applications used for monitoring and data analysis. This gives rise to a possibility of having an internet of things architecture for shop floor machine data processing and further analysis. In this post, we will discuss and implement a possible architecture for ingesting data from multiple CNC lathe machines in an Azure IoT hub, process it with Azure Stream Analytics and use Azure Table Storage, Power BI streaming datasets and Azure Service Bus Queue as data sinks. Further, we will process queue messages using an Azure Function App.

