
⚠️ Resource Notice
All pipelines are designed for iterative processing on small datasets. Run one month at a time on local machines — do not execute against large datasets in a single pass.

For enterprise scale deployment: Cloud infrastructure with distributed processing (AWS EMR, Azure Databricks, or Google Cloud Dataproc) is recommended. Process in parallel batches by scenario or time segment rather than sequentially. Adjust chunk sizes to your available compute resources.
