# jest-dynamoose-issue
Replicate issue where jest takes long time to require dynamoose

Just run:

npm i
npx jest --run-in-band

Notice how testImportPojo tests will run almost instantly but testRequire takes a lot longer
