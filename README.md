# jest-dynamoose-issue
Replicate issue where jest takes long time to require dynamoose

Just run:

npm i

npm run testRequireDynamoose

or for comparison just requiring the aws-sdk

npm run testRequireAwsSdk

Notice how testImportPojo tests will run almost instantly but testRequire takes a lot longer
