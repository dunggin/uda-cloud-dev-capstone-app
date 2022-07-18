## Mkdir to the backend folder
 `cd backend`
## Update all the packages listed to the latest version (specified by the tag config), respecting semver. It will also install missing packages.
`npm update --save`
## Upgrade / fix vulnerabilities in npm packages (Optional)
`npm audit fix`
## For the first time, create an application in your org in Serverless portal
`serverless`
## Next time, deploy the app and note the endpoint url in the end
`serverless deploy --verbose`
## If you face a permissions error, you may need to specify the user profile
`sls deploy -v --aws-profile serverless`
### sls is shorthand for serverless
### -v is shorthand for --verbose