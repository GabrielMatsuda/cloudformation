# cloudformation

<!-- -->
aws cloudformation create-stack --stack-name Init --template-body file://init.yaml --parameters file://init-parameters.json

aws cloudformation update-stack --stack-name Init --template-body file://init.yaml --parameters file://init-parameters.json

aws cloudformation delete-stack --stack-name Init
