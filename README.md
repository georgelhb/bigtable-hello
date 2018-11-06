#### The Java code shows how to Connect to a Cloud Bigtable instance, create a new table, write data to the table, read the data, and delete the table.
---
1) Create a Cloud Bigtable instance: <br/>
```
https://cloud.google.com/bigtable/docs/creating-instance
```
2) Go to the /bigtable-hello/java/hello-world/ folder <br/>
3) Run the Maven job, where [PROJECT_ID] is your GCP project ID and [BIGTABLE_INSTANCE_ID] is your Cloud Bigtable instance ID: <br/>
```
mvn package
mvn exec:java -Dbigtable.projectID=[PROJECT_ID] -Dbigtable.instanceID=[BIGTABLE_INSTANCE_ID]
```
