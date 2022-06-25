# Udagram-iac
#Create Network
./create.sh udacityProject2Infra project2.yml project2-params.json

#Update Network
./update.sh udacityProject2Infra project2.yml project2-params.json

#Create Server
./create-server.sh udacityProject2Infra project2.yml project2-params.json

#Update Server
./update-server.sh udacityProject2Infra project2.yml project2-params.json
 
#LoadBAlancer LInk:
udaci-WebAp-13T7HGMYTE73G-961520270.us-east-1.elb.amazonaws.com