# Azure Java Function

Basic project to demo HTTP triggered and Timer triggered java functions

# Develop

Basically follow [MS Quickstart](https://learn.microsoft.com/en-us/azure/azure-functions/create-first-function-cli-java?tabs=powershell%2Cazure-cli%2Cbrowser)

Run this to bootstrap an empty project :

> `$ mvn archetype:generate "-DarchetypeGroupId=com.microsoft.azure" "-DarchetypeArtifactId=azure-functions-archetype" "-DjavaVersion=8"`

## Triggers

Resource for leveraging different [triggers](https://learn.microsoft.com/en-us/samples/azure-samples/azure-functions-samples-java/azure-functions-java/)

# Deploy

I used vscode and the necessary vsc extensions described [here](https://learn.microsoft.com/en-us/azure/azure-functions/create-first-function-vs-code-java)

It should however be possible to upload the jar via sftp. Check the az function's deployment center for sftp information
