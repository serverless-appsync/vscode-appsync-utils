[Download on the marketplace](https://marketplace.visualstudio.com/items?itemName=bboure.vscode-appsync-utils)

# Snippets

## VTL

### DynamoDB

| prefix                     | description                                                         |
| -------------------------- | ------------------------------------------------------------------- |
| GetItemRequest             | GetItem request template                                            |
| QueryRequest               | Query request template                                              |
| PutItemRequest             | PutItem request template                                            |
| UpdateItemRequest          | UpdateItem request template                                         |
| DeleteItemRequest          | DeleteItem request template                                         |
| TransactWriteItems         | TransactWriteItems query template                                   |
| BatchGetItem               | BatchGetItem query template                                         |
| BatchPutItem               | BatchPutItem query template                                         |
| BatchDeleteItem            | BatchDeleteItem query template                                      |
| Response                   | A basic response template `$util.toJson($ctx.result)`               |
| ConditionalCheckResponse   | Response template with conditional check                            |
| TransactionResponse        | Response template with transaction cancelled check                  |
| GetItemSingleTableRequest  | Get item + children items request template for signle-table design  |
| GetItemSingleTableResponse | Get item + children items response template for signle-table design |

## YAML

Snippets for the configuring the [Serverless Framework AppSync plugin](https://github.com/sid88in/serverless-appsync-plugin/)

| prefix             | description                     |
| ------------------ | ------------------------------- |
| appsync            | A Basic API init template       |
| appsyncCognito     | Cognito user pool configuration |
| appsyncOIDC        | Open ID Connect configuration   |
| unitResolver       | UNIT resolver config            |
| pipelineResolver   | PIPELINE resolver config        |
| functionConfig     | pipeline function config        |
| noneDataSource     | NONE data source config         |
| lambdaDataSource   | AWS Lambda data source config   |
| dynamoDbDataSource | DynamoDB data source config     |
| httpDataSource     | HTTP data source config         |

## GraphQL

| prefix              | description                  |
| ------------------- | ---------------------------- |
| items               | Items getter Query           |
| get                 | Item getter query            |
| create              | Item create query            |
| update              | Item update query            |
| dynamoDBitemsResult | DynamoDB items response type |

## TypeScript

| prefix         | description                             |
| -------------- | --------------------------------------- |
| lambdaResolver | Creates a typed lambda resolver handler |

# Contributing

PRs are more than welcome. :rocket:

# Improvements/Help wanted

It would be great to implement something similar to/that extends the [Serverless IDE extension](https://github.com/threadheap/serverless-ide-vscode) for YAML validation/auto-complete functionalities as an alternative to snippets.
