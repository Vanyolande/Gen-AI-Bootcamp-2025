## Functional Requirements

BOYOtech is a non-profit organization providing AI powered educational services and wants to invest in owning their infrastructure.
The 2 major concerns are about the privacy of user data and the cost of manged services for GenAI will greatly raise cost.

We want to invest in an AI PC of about 10-12K
They have about 250 active students who are located within the city of Bamenda in Cameroon.

## Assumptions

We assume that the open-source LLMs that we choose will be powerful enough to run on hardware with an investment of 10-12k
We are going to hook up a single server in the office to the internet and have enough bandwidth to serve the 250 students.

## Data Strategy

Because of copyrighted materials concerns, we must purchase and supply materials which will be stored for access in our database.
However there is a future possibility of leveraging Amazon S3 for scalable storage.
Data redundancy will be ensured through local backups and Amaazon S3 Glacier for long-term archival storage.

## Considerations

We are considering using IBM Granite because it is a truely opensource model with training data that is traceable so we can avoid any copyright issues
and we are able to know what is going on in the model

More details on IBM Granite:https://huggingface.co/ibm-granite

## Next Steps

1.Finalize hardware specifications based on computational needs and power efficiency.

2.Procure the AI PC and set up necessary software dependencies.

3.Deploy IBM Granite (or an alternative LLM) and test performance.

4.Develop an internal web interface to facilitate student interactions with the AI system.

5.Implement security measures for data access and compliance.

6.Optimize bandwidth usage to ensure smooth operations.

7.Explore AWS credits or sponsorships to support BOYOtech's educational mission.
________________________________________

 