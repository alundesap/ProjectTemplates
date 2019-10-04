proj_name_lc : Project Name Lower Case
proj_name_mc : Project Name Mixed Case
proj_name_uc : Project Name Upper Case
proj_comment : Project Comment/Description
domain_name : Domain Name (do not include hostname ex: conciletime.com use cfapps.xx##.hana.ondemand.com)
account_subdomain : Subdomain name specified in the CF subaccount
jenkins_creds : Jenkins Credentials
cf_region : One of us10, us20, us30, eu10, etc.
cf_org : Cloud Foundry organization for deployment
cf_space : Cloud Foundry space for deployment
```
npm config set @sap:registry "https://npm.sap.com/" ; npm config set registry "https://registry.npmjs.org/" ; npm config set strict-ssl true
mkdir -p target
mta --build-target CF --mtar target/#{proj_name_lc}-CF.mtar build
```
