# Package azure-sb
## Classes
| Class Name | Description |
|---|---|
| @azure-sb.WnsService ||
| @azure-sb.ServiceBusServiceClient ||
| @azure-sb.ServiceBusServiceBase ||
| @azure-sb.ServiceBusService |The ServiceBusServices allows you to work with Microsoft Azure Service Bus. Service Bus provides both queues for sending and receiving messages, as well as push notifications for mobile devices.  Service Bus queues provide both standard message queue functionality as well as publish/subscribe functioanlity. For more information on Service Bus queues, as well as task focused information on using them from Node.js applications, see [How to Use Service Bus Queues](https://www.windowsazure.com/en-us/develop/nodejs/how-to-guides/service-bus-queues/) and [How to Use Service Bus Topics/Subscriptions](https://www.windowsazure.com/en-us/develop/nodejs/how-to-guides/service-bus-topics/).  Service Bus provides push notifications through the Notification Hub. While the ServiceBusService can be used to manage Notification Hubs, you must use the <xref:azure-sb.NotificationHubService> to send messages to mobile devices.|
| @azure-sb.NotificationHubService |The NotificationHubService allows you to send push notifications to iOS, Android, and Windows Store devices.  For more information on Notification Hubs, as well as task focused information on using them from Node.js applications, see [How to Use Service Bus Notification Hubs](https://www.windowsazure.com/en-us/develop/nodejs/how-to-guides/service-bus-notification-hubs/).|
| @azure-sb.MpnsService |The MpnsService class is used to send notifications using the [Microsoft Push Notification Service](http://msdn.microsoft.com/en-us/library/windowsphone/develop/ff402558).|
| @azure-sb.SharedAccessSignature ||
| @azure-sb.GcmService |The GcmService class is used to send notifications using [Google Cloud Messaging](http://developer.android.com/google/gcm/index.html).|
| @azure-sb.ApnsService |The ApnsService class is used to send notifications using the Apple Push Notification Service (APNS). This service is used to communicate with iOS device.|
