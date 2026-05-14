---
title : "Prepare the infrastructure"
date: 2024-01-01
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---

#### Prepare infrastructure

- In this lesson, we will perform the lab in Region **US West (Oregon) us-west-2**

- In this section, we will prepare the resources for the lab by instantiating the **CloudFormation** template.

- You download **CloudFormation** template here [here](https://github.com/AWS-First-Cloud-Journey/AWS-Elastic-Disaster-Recovery-Workshop/tree/main)

1. Access the **CloudFormation** interface

   - Select **Create stack**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0001.png?featherlight=false&width=90pc)

2. In the **Create stack** interface

   - Select **Template is ready**
   - Select **Upload a template file**
   - Select **Next**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0002.png?featherlight=false&width=90pc)

3. For **Stack name**

   - Enter **EDRW**
   - For other parameters, use the default.

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0003.png?featherlight=false&width=90pc)

4. Select **Next**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0004.png?featherlight=false&width=90pc)

5. Select **Next**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0005.png?featherlight=false&width=90pc)

6. Make a selection of **require capabilities**, then select **Create stack**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0006.png?featherlight=false&width=90pc)

7. About 30 minutes later, we will observe the interface and successfully create five stacks.

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0007.png?featherlight=false&width=90pc)

8. See **Outputs** of the stack. We will see if we create a BastionRDP used to connect.

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0008.png?featherlight=false&width=90pc)