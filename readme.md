### Azure Data Factory Pipeline with 2 Dataflows in a single pipeline that uses parquet files as input/output parameters 

See ADFv2 pipeline below, make sure that time to live > 0 is enabled for your dataflows cluster: https://docs.microsoft.com/en-us/azure/data-factory/control-flow-execute-data-flow-activity#data-flow-integration-runtime

![ADFv2 pipeline](ADFv2_pipeline.png "ADFv2 pipeline")
