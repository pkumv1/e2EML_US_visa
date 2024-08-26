# e2EML_US_visa

ML Ops end to end project
##Tools used
Anaconda, Git, Visual Studio, Mongo Db, Evidently(MLops tool), Whimsical(flow chart tool), Jenkins, circle ci (CI/CD tools),

##Workflow

1. constants
2. Entity config for(Data Ingestion, Data Artifact)
3. Connection with Mongo Db
4. Data Access ( import mongo DB as pd dataframs and remove unnecessary columns and check for null / nan values)
5. components(Data Ingestion, Train test split, initiate ingestion )
6. pipeline creation
7. Data Drift detection with evidently
8. Data Validation ( Ensuring data ingested, transformed and provided to model training is correct)

## use following command in git bash to set environment variable of the Mongo DB connection string else you can set in the system environment variables

export MONGODB_URL="your mongo-db connection string"
