# Constrained Device Application (Connected Devices)

## Lab Module 09

Be sure to implement all the PIOT-CDA-* issues (requirements) listed at [PIOT-INF-09-001 - Lab Module 09](https://github.com/orgs/programming-the-iot/projects/1#column-10488503).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 

Our implementation mainly provides CoAP Client Functionality to the CDA. This is mainly done through the creation of a CoapClientConnector, a TelemetryObserverHandler, and a SysPerfDataObserverHandler. We then update the DeviceDataManager to accommodate these changes.

How does your implementation work?

Our implementation works by first creating the CoapClientConnector class and implementing initialization knowledge into it. We then implement a GET, PUT, POST, OBSERVE, and DELETE method into the CoapClientConnector Class. Afterward, we test these methods and have them handled by the TelemetryObserverHandler and the SysPerfDataObserverHandler.

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

URL: [Github link for CDA](https://github.com/BanSuth/piot-python-components/tree/labmodule09)

### UML Design Diagram(s)

NOTE: Include one or more UML designs representing your solution. It's expected each
diagram you provide will look similar to, but not the same as, its counterpart in the
book [Programming the IoT](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).

![image](https://github.com/BanSuth/book-exercise-docs-Group1/assets/62486958/06315832-1c1d-4795-bc70-962a02ed6968)


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

- CoapClientConnectorTest.py
Screenshot:  
![CoapClientConnectorTest](Images/CoapClientConnectorTest_INT_PY.PNG)  

EOF.
