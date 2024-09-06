## Running a flow using multiple node

This approach ensures that each node is completed before proceeding to the next, resulting in a structured and orderly flow. It helps users run multiple nodes in a single run, saving time and enhancing usability.

1. Click on run button to execute the flow.

![sm1](./TestFlowImages/sm1.png)

2. The flow builder will be redirected to the flow report. The flow report page will dynamically update as the flow execution progresses. Here the first suite node is in progress and remaining nodes are in freeze state.

![sm2](./TestFlowImages/sm2.png)

3. After the execution of the first node, delay node will pause the flow execution to a specified time period and then continue the execution of second suite node.

![sm3](./TestFlowImages/sm3.png)

4. Based on the status of the second node, its conditional execution node will trigger the execution of its sub nodes. The Mail node will be responsible for sending the flow's report to the designated email recipient. Finally, the flow will complete its execution via exit node.

![sm4](./TestFlowImages/sm4.png)

> [!Note]
> If the first suite node fails, the remaining nodes will not be executed, and their status will be marked as failed.

If a flow contains both a suite node and a mail node, and the suite node fails, the mail node will be responsible for sending the flow's report to the designated email recipient. Finally, the flow will complete its execution via exit node.