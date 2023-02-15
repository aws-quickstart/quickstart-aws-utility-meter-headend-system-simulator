## quickstart-aws-utility-meter-headend-system-simulator Quick Start
To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo. 
To submit code for this Quick Start, see the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/).

## Overview
This Quick Start deploys a completely serverless solution on the AWS Cloud and simulates the generation of readings by utility meters and inserting into an Amazon Timestream table. If you are unfamiliar with AWS Quick Starts, refer to the [AWS Quick Start General Information Guide](https://fwd.aws/rA69w?).

This Quick Start is for users who want ... 

## Costs
There is no cost to use this Quick Start, but you will be billed for any AWS services or resources that this Quick Start deploys. For more information, refer to the [AWS Quick Start General Information Guide](https://fwd.aws/rA69w?).

## Architecture
Deploying this Quick Start with default parameters builds the following environment in the AWS Cloud.\
![image](docs/images/stack.png)

As shown in the above diagram, this Quick Start sets up the following resources:
- Resource 1
- Resource 2

## Launch the Quick Start
1. Download the [AWS CloudFormation template](templates/headend.system.simulator.yaml) for this stack.

2. In the AWS Management Console, select a region from the top tool bar where Amazon Timestream is available. Please refer to the [Amazon Timestream pricing](https://aws.amazon.com/timestream/pricing/) page for availability.\
![image](docs/images/region_select.png)

3. Navigate to the CloudFormation page, click the "Create stack" button and select "With new resources(standard)".\
![image](docs/images/stack_create_1.png)

4. Select the "Upload a template file" option and choose the template you downloaded in step 1, then click "Next".\
![image](docs/images/stack_create_2.png)

5. More to be filled in later ...