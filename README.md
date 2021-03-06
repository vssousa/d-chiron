# d-Chiron Repository
Welcome to d-Chiron repository. d-Chiron is a Data-intensive Scalable system that manages complex big data workflows and registers big data provenance at runtine to enable user steering and Human in the Loop. d-Chiron utilizes MySQL Cluster as its core in-memory distributed data structure used for managing execution, provenance, and domain dataflow data.

# Contents

In this repository, you find what is necessary to execute d-Chiron either in a cluster or standalone. The original Chiron is also available. d-Chiron data models and user steering OLAP queries are provided. The code for Risers Fatigue Analysis (RFA), a synthetic workflow based on a real case study in oil & gas domain, is available. The workflow modeled and ready to be tested both in d-Chiron and Spark are avaiable. 

- [d-Chiron](d-chiron) 
- [Chiron](chiron)
- [Data models and OLAP queries](datamodels-and-queries/) 
    - [PROV-Df data model](datamodels-and-queries/PROV-Df.png)
    - [d-Chiron's Relational schema](datamodels-and-queries/relational-database-schema-dChiron-RFA.png) 
    - [OLAP queries used to test d-Chiron's user steering and runtime HIL capabilities](datamodels-and-queries/OLAP-queries.sql)
- [Risers Fatigue Analysis synthetic workflow](rfa-synthetic)
    - [RFA activites](rfa-synthetic/rfa-activities)
    - [RFA workflow on Spark](rfa-synthetic/rfa-spark)
    


