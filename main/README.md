# CD12352 - Infrastructure as Code Project Solution
# Michael Yau

## Spin up instructions
chmod +x ./main/scripts/create.sh
./main/scripts/create.sh udagram-network ./main/network/template.yml ./main/network/parameters.json
./main/scripts/create.sh udagram-app ./main/app/template.yml ./main/app/parameters.json

## Tear down instructions
chmod +x ./main/scripts/delete.sh
./main/scripts/delete.sh udagram-network
./main/scripts/delete.sh udagram-app

