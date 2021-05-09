# Twitter-data-stream-into-MySQL-table-using-NiFI

The NiFi was configured in CDH-5.13. Twitter account Keys and Token was taken as API for accessing data from twitter.

The Processors used are:
1. GetTwitter
2. EvaluateJsonPath
3. AttributesToJSON
4. ConvertJSONToSQL
5. ExecuteSQL
6. PutFile
7. LogMessage
