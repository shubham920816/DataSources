# Open Source Connectors for Social Media Platform

## Assumptions:
* Api pushes the data to azure blobs post pulling the data
* Data will be stored in parquet format on azure blobs

## List of Connector

* `Twitter` : Batch Pull of data on basis of search query and date range
* `Reddit` : Batch Pull data on basis of search query and date range
* `Youtube` : Pull data on basis of search query and date range

## Rest request

* API method

````
     http://<docker_container_ip>/ingestion
````
* Body for the request

````
{
   "source" : "Reddit",
   "start_date" : "2017-01-01",
   "end_date" : "2017-01-01"
}
   

````


        
    

