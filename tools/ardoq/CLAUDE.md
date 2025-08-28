# Tools

## Ardoq

Ardoq is the enterprise architecture tools used for IT risk management as well. To adapt it to RM work, we use the Application Risk Management (ARM) metamodel. More on it here (use Fetch): https://help.ardoq.com/en/articles/96957-application-risk-metamodel

### Key points:

I have limited control over APIs, Gremlin queries and advanced ardoq features. All development must be done using the out of the box ARM metmodel as much as possible. This means do not create new fields, leverage only the existing ones. When this is out of the question, create a strong case description as to why I need to for example add a new field in my model.

As an example, to check if controls are deployed in the self-reported system owner part of the analysis I rely on the 'Deploys to' filed on the Control --Deployed to --> Application edge. 