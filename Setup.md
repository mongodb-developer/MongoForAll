Clone this REPO or download the zip.

Create an Account at cloud.mongodb.com and an organisation
( Link to Other Docs)


Create an API Key

Access Manager->CreateAPI Key
    Deployment Key, Org Owner
    ACL Current IP

Get your Org Id: 6171359f54cbe966a43292b7


Install mongocli 
https://docs.mongodb.com/mongocli/stable/install/

Download Binary, MSI ** Windows Defender!! ***

open cmd prompt
mongocli config

CREATE A PROJECT IN ATLAS
----------------------------
mongocli iam project create mongoforall --orgId 6171359f54cbe966a43292b7

GET THE ID
-----------
mongocli iam project list

CREATE A DATABASE CLUSTER IN THT PROJECT (FREE NOT SUPPORTED YET!)
------------------------------------------
mongocli atlas cluster create demoapp --projectId  61713ea337d54a6e0a657dea --provider AWS --region EU_WEST_1 --tier M0



Install Node.JS (FOr the realm-cli tool)



and realm-cli tools]

npm-install -g mongodb-realm-cli

realm-cli login

realm-cli pull --include-hosting --include-dependencies 

