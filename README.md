# nd9991-project-2 - Deploy Infrastructure As a Code (IAC)

## How to create stacks

Execute: sh create-stack.sh stackName stackConfiguration.yml params.json\
Ex for VPC: ./create-stach.sh CloudDevOpsNdStackVPC vpc.yml vpc-parameters.jso\
Ex for Servers: ./create-stack.sh CloudDevOpsNdStackServers server.yml server-parameters.json

## How to update stacks

Execute: sh update-stack.sh stackName stackConfiguration.yml params.json\
Ex for VPC: ./update-stach.sh CloudDevOpsNdStackVPC vpc.yml vpc-parameters.jso\
Ex for Servers: ./update-stack.sh CloudDevOpsNdStackServers server.yml server-parameters.json

## Notes

Update the params accordincly to your needs.\
Don't forget to update the email in the server-parameters.json and the bucket id ( where sits the app files)

