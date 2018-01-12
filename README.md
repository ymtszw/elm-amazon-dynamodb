# elm-amazon-dynamodb

Pure Elm [Amazon DynamoDB][dyn] client.

This is **by no means** full-feature high level client, rather it is experimental thing.

Though it aims to:

- provide Pure Elm client to DynamoDB from server-side Elm code (**which must be considered EXPERIMENTAL**)
- type-safe composition of low-level DynamoDB API requests

Uses [ktonon/elm-aws-core][eac] for request authenticaton (AWS V4 request signing)
