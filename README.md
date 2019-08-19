# PillarD-BIG01-Microsoft-IoT

### Core Subsystems of an IoT Architecture
<img src="https://user-images.githubusercontent.com/31917400/63261251-ec6ee500-c27a-11e9-9aba-7ba231ae841a.jpg"/>

 - 1) devices (and/or on premise edge gateways) that have the ability to securely register with the cloud, and connectivity options for sending and receiving data with the cloud, 
 - 2) cloud gateway service, or hub, to securely accept that data and provide device management (including command and control) capabilities
 - 3) stream processors that consume that data, integrate with business processes. Integration could include storage of informational messages, alarms, sending email or SMS, integration with CRM, and more. 
 - 4) STORAGE: place the data into storage. Storage can be divided into warm path (data that is required to be available for reporting and visualization immediately from devices), and cold path (data that is stored longer term and used for batch processing).
 - 5) a user interface to visualize telemetry data and facilitate device management. 


### Optional Subsystems of an IoT Architecture
<img src="https://user-images.githubusercontent.com/31917400/63261796-415f2b00-c27c-11e9-8000-348fb580f490.jpg"/>

In addition to the core subsystems many IoT applications will include subsystems for: 6) telemetry data transformation which allows restructuring, combination, or transformation of telemetry data sent from devices, 7) machine learning which allows predictive algorithms to be executed over historical telemetry data, enabling scenarios such as predictive maintenance, and 8) user management which allows splitting of functionality amongst different roles and users.






































































































