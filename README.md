#Udacity Udagram

## prerequisites

- Create and download two key pairs form the aws console with names 
    udagram-key and udagram
    
    
##Instructions
    
- Run chmod +x create-stack.sh update-stack.sh delete-stack.sh
- Run ./create-stack.sh your-stack-name udagram-network.yml udagram-network-params-json
- Run ./create-stack.sh your-stack-name udagram-iam.yml udagram-iam-params-json
- Run ./create-stack.sh your-stack-name udagram-s3.yml udagram-s3-params-json    
- Upload udacity.zip to udacity-udagram-s3 before bucket
- Upload udagram.pem and udagram.pem to udagram-key
- Run ./create-stack.sh your-stack-name udagram-bastion.yml udagram-bastion-params-json 
- Run ./create-stack.sh your-stack-name udagram-server.yml udagram-server-params-json    
   
