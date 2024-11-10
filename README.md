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

## Diagram
https://lucid.app/lucidchart/3dac211f-fe4a-48a3-9fa2-387190eb93e1/edit?invitationId=inv_954a37f9-58d2-4efc-bb5d-454021c9b01d

## Deployment
http://udagram--alb-8k31ncxv415f-156881920.ap-southeast-1.elb.amazonaws.com/