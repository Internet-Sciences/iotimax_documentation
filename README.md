# iotimax_documentation
IoTIMAX Network Framework simplifies IoT management: devices, data storage, processing, visualization. Its customized dashboards, reports, key indicators offer insights and predictive analytics, support process improvement. It integrates cloud and local data for non-specialized decision-makers. Robust security, purpose-built for Industrial IoT with scientific methods, mathematical models and data analytics.

# Getting started
To get started with the project you need three things:
1. A project name
2. A valid API Key (you can recieve one by contacting us, but the key will be temporary)
3. Your .env file in json format. It needs to include variables for databases and cloud access, like aws_rds_endpoint, aws_rds_password, aws_access_key_id, aws_secret_access_key for aws or ibm_api_key, ibm_service_instance_id and endpoint url for aws cos. To make it easy, create a .env you would make for a django project where you are adding a cloud database.

There are some optional variables too
1. vpc_config, which chooses whether you want a vpc
2. vpc_name for name of vpc
3. zone for IBM vpc zone
4. subnet cidr for vpc subnet
5. subnet_name for subnet name

The outputs will be frontend_url and backend_url. Backend_url will be the api, while frontend_url is the frontend url for the front facing product.

