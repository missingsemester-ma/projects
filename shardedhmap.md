# Sharded HashMap

# Problem statement

In this project, you are asked to make a simple HTTP API that mimics the functionalities of a HashMap. 

Since we will assume that data cannot be held by a single machine, we will want to shard the data written to the HashMap using a scheme of your choice.

The API should look like:

```
GET         /api/<key> 
POST        /api              { key: <key>, value: <value> }
DELETE      /api/<key>
```

## Evaluation Criteria

1. All the API routes are present and respect the rough definition above.
2. Data is not stored all in a single location but a sharding scheme is implemented.
3. A `README.md` file with documentation of how to build / run the project and any dependencies that should available on the host.
4. Documentation also should highlight the overall design and any tradeoffs performed and explain why.

## Submission

You can simply send an email to `hello@missingsemester.io` with the subject line `Missing Semester Spring Cohort: <Full Name> Submission`  The email should contain a link to a public Github repository for the project with all the necessary documentation.
