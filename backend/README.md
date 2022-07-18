## `cd backend` 
Mkdir to the backend folder

## `npm update --save`
Update all the packages listed to the latest version (specified by the tag config), respecting semver. It will also install missing packages

## `npm audit fix`
Upgrade / fix vulnerabilities in npm packages (Optional)

## `serverless`
For the first time, create an application in your org in Serverless portal

## `serverless deploy --verbose`
Next time, deploy the app and note the endpoint url in the end

## `sls deploy -v --aws-profile serverless`
If you face a permissions error, you may need to specify the user profile

#### sls is shorthand for serverless
#### -v is shorthand for --verbose