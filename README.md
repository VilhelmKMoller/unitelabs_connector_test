# unitelabs_connector_test
 Test unitelabs connector for SILA 

# Questions
What is the differnece between the SILA unitelabs and the LARA Arduino starter project with the XML part? 

Unitelabs has a platform that is running on the main server(ubuntu server)

CDK is the unitelabs developer kit. It works the same as the SILA developer kit, with minor alterations. 
CKD contains:
- Connector: The connector displayed to the platform
- Driver: The low level code connecting to the the connector to the device firmware.
- edge gaitwais: The gait way used by the connector to the server. 
- Module ???
- Property: A static/semi-static property displayed by server. Name, type, UUID. 
- Sensor: data streamed. This data can be subscribed to by server. 
- Control: something that requires input parameter such as send open to open door on PCR machine. Either returns a stream of respones while machine is moving and ends with final response or send one final respons. 

- Feature: A feature is an action catagory for connector(device). Such as open door on PCR machine. A feature can be a command or a propperty. Each command or property has two cattegories. Observable and unobservable. 


python SDK is for controling LHR.