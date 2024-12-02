# Try Tinybird. Win an iPhone 16.
Complete the steps below for your chance to win an iPhone 16. 1 in 25 people will win, but the more steps you complete, the better your odds!

The deadline to finish is **Friday, December 13th at 11:59 PM EST**. Winners will be announced the following week. Terms and conditions can be found [here](https://tbrd.co/aws-challenge).

## TL;DR Steps
| Step | Entries | Time |
| :--- | :------ | :--- |
| 1. [Sign up](https://tbrd.co/reinvent_challenge_signup) for a free Tinybird account | 🎟️ 1 entry | ⏳ 30 seconds |
| 2. Create a Data Source | 🎟️ 2 entries | ⏳ 1 minute |
| 3. Build a Pipe | 🎟️ 3 entries | ⏳ 2 minutes |
| 4. Publish your Pipe as an API Endpoint | 🎟️ 5 entry | ⏳ Instant |
| 5. Share your work on social media and tag Tinybird | 🎟️ 10 entries | ⏳ 1 minute |

For even more entries, check out the **Extra Credit** below.

> ⚠️ Don't forget to submit your published API Endpoint URL [here](https://forms.gle/HiRTFjbRy9di7Mzt7).

## Detailed Steps

### Step 1: Sign up for a free Tinybird account
🎟️ 1 entry | ⏳ 30 seconds

[Sign up for free here](https://tbrd.co/reinvent_challenge_signup). No credit card required. No time limit.

Once you've signed up, create a Workspace in an AWS region.

#### Resources:
- [Tinybird Quick Start Guide](https://www.tinybird.co/docs/quick-start)
- [Tinybird Concept: Workspaces](https://www.tinybird.co/docs/concepts/workspaces)

### Step 2: Create a Data Source
🎟️ 2 entries | ⏳ 1 minute

Create a Data Source from the supplied [remote CSV file](https://reinvent-challenge.s3.us-west-2.amazonaws.com/black_jack_results.csv) containing theoretical blackjack results.

#### Resources:
- [Tinybird Concept: Data Sources](https://www.tinybird.co/docs/concepts/data-sources)
- [Video: Ingest data from a file](https://www.tinybird.co/docs/screencasts?video=ingest-data-from-a-file)

### Step 3. Build a Pipe
🎟️ 3 entries | ⏳ 2 minutes

Use your SQL skills to query the Data Source you created, and determine the odds of the dealer winning based on their first card, ordered by decreasing win percentage.

Your results should look something like:

| dealer_card | win_pct |
| - | - |
 A | 0.5957 
 K | 0.5437 
 10 | 0.5343 
... | ...

#### Resources:
- [Tinybird Concept: Pipes](https://www.tinybird.co/docs/concepts/pipes)
- [Best practices for faster SQL](https://www.tinybird.co/docs/query/sql-best-practices)
- [Video: Create a Pipe](https://www.tinybird.co/docs/screencasts?video=create-a-pipe)

### Step 4. Publish an API Endpoint
🎟️ 5 entries | ⏳ Instant

Tinybird lets you publish any Pipe as a scalable REST API Endpoint in a click. From the Pipe UI, click the big green **Create API Endpoint** button to create your Endpoint! 🎉

Once your API Endpoint is published, copy the HTTP Endpoint and [submit it here](https://forms.gle/HiRTFjbRy9di7Mzt7) for credit.

#### Resources:
- [Tinybird Overview: API Endpoints](https://www.tinybird.co/docs/publish/api-endpoints/overview)
- [Video: Publish an API Endpoint](https://www.tinybird.co/docs/screencasts?video=publish-an-api-from-an-sql-pipe)

### Step 5. Share your experience on social media
🎟️ 10 entries | ⏳ 1 minute

Share your experience using Tinybird on social media. Tell us what you like (or don't like) and show off your work!

Make sure to follow Tinybird and tag us for credit:
- [LinkedIn](https://www.linkedin.com/company/tinybird-co)
- [Twitter](https://x.com/tinybirdco)
- [Threads](https://www.threads.net/@tinybird_co)
- [Bluesky](https://bsky.app/profile/tinybirdco.bsky.social)

> Want an Easter Egg? Find us on Instagram...

## Extra Credit
Loving Tinybird so far? Want to earn more raffle entries? Here's some extra credit you can try.

> ‼️ You can submit proof of extra credit through the [same form](https://forms.gle/HiRTFjbRy9di7Mzt7) as the main challenge.

### Add a Query Parameter to Your API
🎟️ 5 entries | ⏳ 1 minute

Add a query parameter to the API Endpoint you built in the main challenge so the API returns the odds for a specific card (e.g. 'A' or 'K').

#### Resources:
- [Tinybird Docs: Using query parameters](https://www.tinybird.co/docs/query/query-parameters)
- [Video: Add query parameters to your APIs](https://www.tinybird.co/docs/screencasts?video=add-query-parameters-to-your-apis)

### Create a Chart
🎟️ 10 entries | ⏳ 3 minutes

Use the Tinybird Chart Library to create a chart that displays the data from your Endpoint. Note: you may need to update your Endpoint or create a new one.

#### Resources:
- [Tinybird Docs: Charts](https://www.tinybird.co/docs/publish/charts)
- [Video: Build with Tinybird Charts](https://www.tinybird.co/docs/screencasts?video=build-fast-charts)

### Build a Real-Time Analytics pipeline with DynamoDB
🎟️ 20 entries | ⏳ 15-30 minutes
Have data in Dynamo? Connect it to Tinybird and build your own real-time analytics API.

If you don't have DynamoDB data, you can use our example data generator in the [extra_credit](https://github.com/tinybirdco/tinybird-reinvent-challenges/tree/main/extra_credit) folder.

#### Resources:
- [Tinybird Docs: DynamoDB Connector](https://www.tinybird.co/docs/ingest/dynamodb)
- [Video: Import and sync from DynamoDB](https://www.tinybird.co/docs/screencasts?video=import-and-sync-data-from-dynamodb-to-tinybird-for-real-time-analytics)

## Have questions?
Come find us at AWS re:Invent! We're at Booth 1856. We're happy to talk you through the use case.

Or, [join our Slack Community](https://www.tinybird.co/community) to get live help from Tinybird power users.