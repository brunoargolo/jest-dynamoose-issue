# jest-dynamoose-issue
Replicate issue where jest takes long time to require dynamoose

Just run:

npm i

npm run testRequireDynamoose

or for comparison just requiring the aws-sdk

npm run testRequireAwsSdk


The SDK version runs is about 2 seconds and the dynamoose one in a little over 20s.
