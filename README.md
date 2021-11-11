# ansible_playbook
Repository for playbook tasks to automate some of the process.
<h1>Purpose</h1>

The purpose of this repository is to create a space for reference on the uses of Ansible to do quick deployments or changes in a system or creating system configurations with more ease.
There are many options to fast infrastructure deployments such as AWS CloudFormation, Boto3 Python Module, or even AWS CLI, Ansible is just another tool that can be readily used for the purpose of management
 as. The benefits of this application over AWS and their own is the ability to manage existing systems already in place as the software can communicate with EC2 or even other cloud/on-premise systems with little constraints
 in comparison to AWS's own tools that are specific to only AWS infrastructure. It should be noted that Ansible does utilize the boto3 module during the deployments of infrastructure as both routes towards IAC(Infrastructure as Code) utilize the Python language.
 
While this tool is amazingly simple to use due to its readability, it should be noted that boto3 and AWS-CLI still have some advantages as the core function of those tools have functions to pull existing data and reference them for change, whereas Ansible seems to require data to be placed into the code prior to runtime. It's unclear as of right now whether or there is an additional function to list or specify targets of infrastructure outside of utilization of tags.
