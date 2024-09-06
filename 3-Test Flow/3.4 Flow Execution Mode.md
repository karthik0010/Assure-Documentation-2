


# Flow Execution

The flow can be easily managed by users according to their preferences. They can use a single node such as a suite node, to execute the flow, or they can use multiple nodes, such as a delay, condition, action, and suite node, to direct the flow.

## Mode of Execution 

### Serial Mode

Serial execution of a flow refers to running nodes in a sequential manner, where each testcase completes before the next one begins.
 
![MODE1](./TestFlowImages/MODE1.png)

1.Click on run button at the flow builder to execute the flow.

![MODE2](./TestFlowImages/MODE2.png)

2.The flow builder will be redirected to the flow report page where user can observe the run status of each suite node. At first, the status of the flow will be "in progress" 

![MODE3](./TestFlowImages/MODE3.png)

3. Clicking on the suite node lets you view a summary of the live report, where you can observe the test cases running sequentially, one after another.

![MODE4](./TestFlowImages/MODE4.png)

Once all test cases within the suite has been executed, the node status transitions from InProgress to a passed state or failed, and the color of the suite node changes to green if passed and red if failed.

![MODE 5](./TestFlowImages/MODE5.png)

### Parallel Mode

Parallel mode in a flow allows multiple testcase to be executed simultaneously rather than sequentially. This increases efficiency by enabling different test cases to run at the same time, reducing overall execution time.
          
![MODE6](./TestFlowImages/MODE6.png)

1. Click on run button at the flow builder to execute the flow.

![MODE7](./TestFlowImages/MODE7.png)

2. The flow builder will be redirected to the flow report page where user can observe the run status of each suite node.

![MODE 8](./TestFlowImages/MODE8.png)

Once all test cases within the suite has been executed, the node status transitions from InProgress to a passed state or failed. According to the suite result .

![MODE9](./TestFlowImages/MODE9.png)
