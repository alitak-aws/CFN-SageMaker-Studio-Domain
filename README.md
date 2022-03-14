## Lab Environment Setup

## Day 1

The first step is to deploy a CloudFormation template that will perform much of the initial setup work for you. In another tab, login to your AWS account. Once you have done that, open the link below in a new tab (right click on the icon below) to start the process of deploying the items you need via CloudFormation.

[![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=workshop&templateURL=https://cf-templates-j7hsyuqasrp5-us-west-2.s3.us-west-2.amazonaws.com/2022070ddG-SM_studio_cfn.yaml)

Follow along with the screenshots below if you have any questions about deploying the stack.


Start by clicking `Next` at the bottom as shown:
<br ><br />

![StackWizard](readme/img/fig1.jpg)
<br ><br />

Select the  `SageMakerSecurityGroupIds`, `SageMakerStudioSubnetIds`, and `VPCId` from the drop-down lists. Then, click `Next` at the bottom of the page.

 and 
 without changing anything until you get to the page shown below. Check the `I acknowledge that...` box and then 

<br ><br />
![StackWizard4](readme/img/fig2.jpg)
<br ><br />

Keep clicking `Next` until you reach the following page. Select `I acknowledge that AWS CloudFormation might create IAM resources with custom names` box and then click `Create stack` as shown below.

![StackWizard5](readme/img/fig3.jpg)
<br ><br />

For a few minutes CloudFormation will be creating the resources described above on your behalf. 



Once it has completed you'll see green text like below indicating that the work has been completed. 

<br ><br />
![StackWizard5](readme/img/fig4.jpg)

<br ><br />
Right-Click and open [this link](https://us-east-1.console.aws.amazon.com/sagemaker/home?region=us-east-1#/studio) in a new tab to go to your SageMaker Studio console. In the list of `Users`, you should see  a user named as `defaultuser`. There is drop-down menu. Go ahead and select `Studio` from the list of `Launch app` as shown below:

<br ><br />
![Sagemaker](readme/img/fig5.jpg)
<br ><br />

You should see the SageMaker Studio page at this point:

<br ><br />
![Sagemaker](readme/img/fig6.jpg)
<br ><br />

At this step, you should clone the repository prepared for the lab today. https://github.com 

<br ><br />
![Sagemaker](readme/img/fig7.jpg)
<br ><br />

