# Gateway Device Application (Connected Devices)

## Lab Module 09

Be sure to implement all the PIOT-GDA-* issues (requirements) listed at [PIOT-INF-09-001 - Lab Module 09](https://github.com/orgs/programming-the-iot/projects/1#column-10488503).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 

How does your implementation work?

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

URL: [Github link for GDA](https://github.com/BanSuth/piot-java-components/tree/labmodule09)

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

- CoapClientConnectorTest (PIOT-GDA-09-003)  
This is running the testConnectAndDiscover() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_3.PNG)

- CoapClientConnectorTest (PIOT-GDA-09-004)  
This is running the testConnectAndGetCon() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_4_2.PNG)

- CoapClientConnectorTest (PIOT-GDA-09-004)  
This is running the testConnectAndGetNon() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_4_1.PNG)

- CoapClientConnectorTest (PIOT-GDA-09-005)  
This is running the testConnectAndPutCon() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_5_1.PNG)

- CoapClientConnectorTest (PIOT-GDA-09-005)  
This is running the testConnectAndPutNon() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_5_2.PNG)


- CoapClientConnectorTest (PIOT-GDA-09-006)  
This is running the testConnectAndPostCon() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_6_1.PNG)

- CoapClientConnectorTest (PIOT-GDA-09-006)  
This is running the testConnectAndPostNon() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_6_2.PNG)

- CoapClientConnectorTest (PIOT-GDA-09-007)  
This is running the testConnectAndDeleteCon() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_7_1.PNG)

- CoapClientConnectorTest (PIOT-GDA-09-007)  
This is running the testConnectAndDeleteNon() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_7_2.PNG)

- CoapClientConnectorTest (PIOT-GDA-09-008)  
This is running the testObserve() test.  
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_8_1.PNG)


EOF.
