#### Create AirlineReservation Table in DynamoDB
- From [DynamoDB](console.aws.amazon.com/dynamodbv2), select **Create table**
- **Table name**: AirlineReservation
- **Partition key**: RecordLocator
- **Sort key**: ActivityDateTime

#### Create User for DynamoDB
- From [IAM](console.aws.amazon.com/iam), go to Users, then select **Create user**
- Give it a name, then select **Attach policies directly** to set permissions
- Search for **AmazonDynamoDBFullAccess** and select it to attach
- Finish creating the user and save the user access keys

#### Seed the AirlineReservation Table
Open this project to the extra_credit directory in VS Code or editor of choice.

Open a new terminal and
- Install the dependencies
```bash 
npm i
```
- Create a new file `.env.local` in the project's root directory
```bash
cp .env.example .env.local
```
- Update AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, and AWS_REGION
- Run the seed script from the project's root directory
```bash
node seed-dynamodb.mjs
```

*Note*: The `seed-dynamodb.mjs` file will generate 50 reservations at a time. Feel free to update the number or run it multiple times.