# 5. Data Storage

Date: 2024-02-20

## Status

Accepted

## Context

We would need a database to store all the student and staff information. the database should be capable of retrieving and manipulating all the data in the database. Moreover, the database should be capable of storing all kinds of data including student's images, schedules and personal data.

## Decision

We will be using the functional SQL database for the university, as it does provide easy storage and retrieval of data.

## Consequences

1.  The functional database is not as flexible as other databases like MongoDB.
2.  As all the data is going to follow a similar structure, it would be easy to operate with.
3.  The SQL has a common standard to follow, which makes it easy to understand and write on various vendor's platforms.
