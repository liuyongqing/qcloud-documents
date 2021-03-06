After you purchase and use the Cloud Monitor supported products, you can monitor the status and metrics of these products and set alarm policies accordingly in the Cloud Monitor Console.

## Monitoring Cloud Product Resources

Cloud Monitor offers free monitoring of resources on Tencent Cloud.

1. Cloud Monitor can collect basic monitoring metrics and store monitoring metric data automatically and accurately in real time.
2. Users can view the metric data of these products in the form of custom graphs and configure [alarms](https://cloud.tencent.com/document/product/248/6126) via [Cloud Product Monitoring]() and [Dashboard](), and also pull these data for further use and analysis via [API](https://cloud.tencent.com/doc/api/405).

Most cloud services' monitoring metrics can be collected and displayed automatically, eliminating the need of manual configuration.
Some cloud services (such as CVM monitor and CPM monitor) need to install and run monitoring agent before collecting the monitoring data. You can choose auto installation when purchasing the resources for these cloud services.

## Alarm Service

Cloud Monitor provides timely and personalized alarm service.

1. Based on the existing monitoring metric data, you can use the default alarm settings or customize the alarm settings for the cloud resources and custom metrics.
2. You can set different resource alarm polices (such as event alarm, failure alarm, and threshold alarm) to meet the requirements of different OPS scenarios.
3. You can distinguish alarm levels by setting different frequencies and logics, and receive alarm messages via different channels by configuring mobile number, Email, and callback URL.

## Multi-dimensional Graph Display

Cloud Monitor allows you to view existing monitoring data in various custom graphs.

1. You can view the monitoring data of the cloud resources at [cloud service console monitoring float window/monitoring details](https://cloud.tencent.com/document/product/248/6142). The latest data is displayed in curve by default.
2. You can subscribe key metrics, customize how to display and compute metrics, sort and compare them in lists and charts, troubleshoot exceptions, and analyze failures at [Dsahboard](https://cloud.tencent.com/document/product/248/13118).
3. You can view the monitoring data and alarm information of all cloud services under your account at [Cloud Product Monitoring](https://cloud.tencent.com/document/product/248/13526).

## Monitoring Custom Data

Cloud Monitor allows you to report custom monitoring metrics independently.

1. In the [CCM](https://cloud.tencent.com/document/product/248/13525), you can upload the concerned metrics (such as the data generated by application) to Cloud Monitor via Tencent Cloud basic network for real-time computing and storage, and analyze failure and predict trends based on what displays at frontend, alarms as well as underlying basic metrics.
2. You can report alarm messages and send alarms using the API in [Custom Messages](https://cloud.tencent.com/document/product/248/6218), and then your concerned data will be sent to you via free SMS and Email.
