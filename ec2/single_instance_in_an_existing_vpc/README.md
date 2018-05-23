# How to execute


aws --profile <default> cloudformation create-stack --stack-name MyTestStack \
    --template-body file://single_instance_private_subnet.yaml \
    --parameters file://parameters.json \
    --tags file://tags.json \
    --region us-east-1
