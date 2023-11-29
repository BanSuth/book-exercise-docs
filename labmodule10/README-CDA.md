# Constrained Device Application (Connected Devices)

## Lab Module 10

Be sure to implement all the PIOT-CDA-* issues (requirements) listed at [PIOT-INF-10-001 - Lab Module 10](https://github.com/orgs/programming-the-iot/projects/1#column-10488510).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 

How does your implementation work?

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

URL: [Github link for CDA](https://github.com/BanSuth/piot-python-components/tree/labmodule10)

### UML Design Diagram(s)

NOTE: Include one or more UML designs representing your solution. It's expected each
diagram you provide will look similar to, but not the same as, its counterpart in the
book [Programming the IoT](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).


### Unit Tests Executed

NOTE: TA's will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

None for this module.

### Integration Tests Executed

NOTE: TA's will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

## MqttClientPerformanceTest (PIOT-INT-10-001)  
This is running the testConnectAndDisconnect(), testPublishQoS0(), testPublishQoS1(), testPublishQoS2() tests.  
Screenshot:  
![MqttClientPerformanceTest](Images/CDA/MqttClientPerformanceTest_1.PNG)

## MqttClientConnectorTest (PIOT-CDA-10-001)
Screenshot:  
![MqttClientConnectorTest](Images/CDA/MqttClientConnectorTest_001.PNG)

## DeviceDataManagerCallbackTest (PIOT-CDA-10-002)
Screenshot:  
![DeviceDataManagerCallbackTest](https://github.com/BanSuth/book-exercise-docs-Group1/assets/80484349/7a61a224-44c5-43c2-8fe1-2c3e105e7f81)

## MqttClientConnectorTest (PIOT-CDA-10-003)
This is running the testNewActuatorCmdPubSub() test.  
Screenshot:  
![MqttClientConnectorTest](Images/CDA/MqttClientConnectorTest_003.PNG)

## DeviceDataManagerIntegrationTest (PIOT-CDA-10-004)
Screenshot:  
![DeviceDataManagerIntegrationTest](Images/CDA/DeviceDataManagerIntegrationTest_004.PNG)

## PIOT-INT-10-003 (Running CDA and GDA Together)
CDA Output Screenshot:
![PIOT-INT-10-003](Images/CDA/PIOT-INT-10-003.PNG)

## PIOT-INT-10-004 (Running CDA and GDA Together with TLS)
CDA Output Screenshot:
![PIOT-INT-10-004](Images/CDA/PIOT-INT-10-004.PNG)

EOF.
