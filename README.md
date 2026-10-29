# Exported benchmark queries

This directory contains standalone copies of the query definitions used by the
benchmark. It does not modify or depend on the original benchmark source tree.

## Experiment identifiers

- `USER_ID_1`: `297358566`
- `USER_ID_2`: `301529877`

The text templates use `{{USER_ID_1}}` and `{{USER_ID_2}}`. The C# export keeps
the same placeholders and replaces them at runtime through method arguments.

## Included benchmarks

- `FindFriends`
- `FindFriendsOfFriends`
- `FindMutualFriends`
- `CountFriends`
- `FindUsersWithMoreThanNFriends`

## Files

- `mongodb_queries.txt`: MongoDB aggregation command templates.
- `arangodb_queries.txt`: ArangoDB AQL templates.
- `orientdb_queries.txt`: OrientDB SQL and MATCH templates.
- `terminusdb_queries.txt`: TerminusDB WOQL JSON templates.
