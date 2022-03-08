# cloudformation-cross-stack-reference-

Step1 - Deploy a sample network configuration stack with the network template provided. For stackname use: SampleNetworkCrossStack

Step2 – Deploy a new stack that will setup a Linux EC2 instance (Web server) and reference the sample network stack previously created. Deploy template in us-west-2 region.

•	Reference all available variables from SampleNetworkCrossStack.

•	Create a Mapping function to dynamically choosing regions.

•	Allocate an Elastic IP address using resources.

•	Create parameters for requesting user inputs as much as possible.

•	Output the values of the private IPv4 address and DNS name of the EC2 instance.
