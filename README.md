# curl

curl --location --request POST 'https://ap-south-1.aws.data.mongodb-api.com/app/data-xnakx/endpoint/data/v1/action/insertOne' \
--header 'Content-Type: application/json' \
--header 'Access-Control-Request-Headers: *' \
--header 'api-key: o87MBXtxmrtHBATmbQHxDrq2cYGmjxhfmh7szC8fn8C22qFJ2i1My4bGUEmtdJQi' \
--data-raw '{
    "collection":"test",
    "database":"test",
    "dataSource":"Cluster0",
    "document": 
            {
              "latitude":64.678,
              "longitude":73.345}             
        })"
}'
