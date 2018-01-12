# elm-amazon-dynamodb

Pure Elm [Amazon DynamoDB][dyn] client.

[dyn]: https://aws.amazon.com/dynamodb/

**This is by no means full-feature high level client**, rather it is an experimental thing.

Though it aims to:

- provide Pure Elm DynamoDB client implementation
- provide Elm DynamoDB client that works in server-side Elm code (**which itself [must be considered EXPERIMENTAL][exp]**)
[exp]: https://github.com/elm-lang/projects/blob/master/notes/on-general-purpose.md
- type-safe composition of low-level DynamoDB API requests

Uses [ktonon/elm-aws-core][eac] for request authentication (AWS V4 request signing)

[eac]: https://github.com/ktonon/elm-aws-core
