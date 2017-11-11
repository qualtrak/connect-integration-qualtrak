# connect-integration-qualtrak

## Amazon Connect Integration -- Evaluate for Amazon Connect

**Evaluate for Amazon Connect** by **Qualtrak Solutions** is a high standard agent evaluation (Quality Monitoring) and online learning solution that will help you to develop the skills of your agents and achieve the required standards in customer service, customer loyalty, brand values adherence, cross and up-selling, first call resolution, optimum call handling time and much more. It is easy and intuitive to use and highly scalable. 

Evaluate is seamlessly integrated directly to the **Amazon Connect** call recording service and uses the Contact Trace Records (CTR) to enable supervisors to find calls that contain the appropriate ‘situations’ which match precisely the agent’s personal performance improvement needs e.g. how well did the agent transfer the customer’s call to another agent; if the customer was placed on hold, did the agent return to the customer if the hold-time was greater than x seconds and apologize; if the call resulted in the agent placing the customer on hold more than y times, was this caused by the agent failing to gain an understanding of the customer’s needs and causing the length of the call to be longer than it needed to be, etc. For the supervisor to be able to coach their agents on personal needs, it requires the right calls to be found (using CTRs) which contain the appropriate ‘situations’. Evaluate does not require the use of a third-party call recorder and therefore avoids additional costs.

Typically, the cost of agents equates to around 55% of the total contact center costs. Being able to manage effectively the performance of agents and be able to maximize both the productivity and quality of customer interactions, requires a robust **Quality Management programme** to be implemented which continuously measures agent performance, identifies individual improvement needs and delivers to the agents appropriate online learning/coaching. Evaluate provides supervisors and managers with the required tools to support their Quality program.

**Evaluate for Amazon Connect** delivers significant value by including the following key benefits:

- rate the quality of calls against defined standards and create performance metrics
- track the performance of agents and benchmark agent and team performance
- create ‘evaluation templates’ which include the required skills and knowledge to meet critical standards e.g. regulatory compliance, cross and up-selling and much more
- include weightings for each evaluation element (questions) in order to produce headline scores
- include ‘auto-fail’ and calibration of supervisors’ evaluation consistency and objectivity
- provide agent coaching feedback comments, supportive call segments and learning attachments to each individual question in order that evaluated calls can also provide continuous online learning
- use the available easy to use/preformatted reports to track performance and set goals

**Evaluate for Amazon Connect** is a multi-tenanted solution designed to be used by customers with multiple locations (of all sizes) using a common active directory. The solution is designed to be used by every type of user including supervisors, agents, homeworkers, branch network employees, quality and compliance auditors, trainers and managers/senior executives. 

## Deployments options

Your customer's organisation must be using Active Directory, either in AWS (e.g. SimpleAD) or on premise with **Direct Connect**


- **Option 1** : Deploy for a new VPC 

  This option will create a new VPC, deploy the [Data Streaming](https://aws.amazon.com/quickstart/connect/data-streaming/) stack and **Evaluate for Amazon Connect**

    Template: `evaluate-json-master.template`

- **Option 2** : Deploy for an existing VPC with **Data Streaming**

  This option will deploy the [Data Streaming](https://aws.amazon.com/quickstart/connect/data-streaming/) stack and **Evaluate for Amazon Connect** into an existing VPC

    Template: `evaluate-datastreaming-json-master.template`

- **Option 3** : Deploy for an existing VPC without **Data Streaming**

  This deployment will deploy **Evaluate for Amazon Connect** into an existing VPC

    Template: `evaluate-json.template`

![Architecture](http://s3.amazonaws.com/Qualtrak/Quick%20Start%20Architecture%20Diagram.JPG)
