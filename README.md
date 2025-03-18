# Designing-a-Peta-Bytes-Application
system design explanation with pseudo-code and architectural choices for building a Petabyte-scale application

✅ Data Layer: Databricks (Delta Lake)
✅ Application Layer: Salesforce (Customer/Order Journey)
✅ Legacy OSS: Network Inventory / Provisioning System

And handling the following data operations:

Store & retrieve data
Cache expensive computations
Search
Messaging queues
Stream processing
Batch processing

🔄 Data Store & Retrieve Layer (Databases)
Design:
Use Delta Lake on Databricks for:
Versioned, reliable, ACID-compliant storage
Scalability for Petabyte-scale
Schema evolution for legacy OSS systems
