# Welcome to your CDK TypeScript project!

This is a blank project for TypeScript development with CDK.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template

===============

  132  rm README.md
  133  cdk init --language=typescript
  134  git add .
  135  git commit -am "CDK init with typescript"
  136  git push origin master
  137  npm test
  138  cdk bootstrap
  139  cdk diff
  140  cdk list
  141  npm test
  142  cdk deploy
  143  cdk diff