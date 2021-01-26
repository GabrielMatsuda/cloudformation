# cloudformation

<!-- -->
aws cloudformation create-stack --stack-name Init --template-body file://init.yaml --parameters file://init-parameters.json --region sa-east-1

aws cloudformation update-stack --stack-name Init --template-body file://init.yaml --parameters file://init-parameters.json --region sa-east-1

aws cloudformation delete-stack --stack-name Init --region sa-east-1
