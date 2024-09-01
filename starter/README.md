# CD12352 - Infrastructure as Code Project Solution
# Matthias Rohe

## Network diagramm:

<img src="https://github.com/MattRo74/udacity-iac-project/blob/master/diagram_ppt/Diagram.jpg">

Link to working test: udagra-WebAp-XMvRKMzP5HGP-854015396.us-east-1.elb.amazonaws.com


## Spin up instructions

Create Network: ./create_network.sh udagraminfra network.yml network-parameters.json
Create Server: ./create_server.sh udagramserver udagram.yml udagram-parameters.json


## Tear down instructions

Delete Network: ./delete_network.sh udagraminfra
Delete Server: ./delete_server.sh udagramserver

## Other considerations

Configuration of the CLI

(1) Creating IAM User:

<img src="https://github.com/MattRo74/udacity-iac-project/blob/master/images/01_IAM_USER/01_Create_IAM_User.jpg">

(2) Set Permissions:

<img src="https://github.com/MattRo74/udacity-iac-project/blob/master/images/01_IAM_USER/01_AdminAccess.jpg">

(3) Review and Create:

<img src="https://github.com/MattRo74/udacity-iac-project/blob/master/images/01_IAM_USER/03_Review_Create.jpg">

(4) Create Access Key:

<img src="https://github.com/MattRo74/udacity-iac-project/blob/master/images/01_IAM_USER/04_Create_Access_Key.jpg">

(5) Create Access Key CLI:

<img src="https://github.com/MattRo74/udacity-iac-project/blob/master/images/01_IAM_USER/05_Access_Key_for_CLI.jpg">

(6) Download Access Keys:

<img src="https://github.com/MattRo74/udacity-iac-project/blob/master/images/01_IAM_USER/06_Download_AccessKey.jpg">

(7) Configure CLI:

<img src="https://github.com/MattRo74/udacity-iac-project/blob/master/images/01_IAM_USER/07_Console_AWS_Configure.jpg">

(8) Finish Configuration

<img src="https://github.com/MattRo74/udacity-iac-project/blob/master/images/01_IAM_USER/08_Console_Finish_Configuration.jpg">