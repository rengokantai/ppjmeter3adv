# ppjmeter3adv
### Random and Runtime Controllers
note
- Random controller is one of the widely used controller in JMeter
- It is used for simulating certain real world scenarios
- It selects one of the samplers in it randomly and runs it every time
- It is a very useful element in a load testing project



## 3. Overview of Test Controller
### Listeners
Listener
- A listener is a component that shows the results of the samples, the results or imformation gathered by listeners can be shown
in the form of a tree, table, graph or a log file
- Different listeners display the response information in different ways.
Jmeter creates results of a test run a Jmeter Text Logs(JTL), 
- The `configure` button can be used to specify which fields to write to file, and whether to write it as csv or xml, csv is much better than xml. suggest use csv



### Aggregate Report 
Report
- Creates a table row for each differently named represent in your test
-
- Once the test is done, the throughput is the actual throughput for the duration of the entire test


## 4. Designing Test Plan
### Workload Designing
Thread group.
number of threads:10, ramp-up period 20, means each user will enter the system every 2 seconds


### script validation


### Master Slave Configuration
note
- is a type of testing where load is generated from multiple
machines on a network
- The test is managed by a central as test controller which is on
the same network
- The test controller is called as master machine and the load 
generating agents are called as slave machines
