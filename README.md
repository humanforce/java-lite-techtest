# java-lite-techtest

## Build a RESTful API using Spring Boot with below endpoints:
(use database of your choice, or even in-memory data is fine)

POST `/authors`

PATCH `/authors/:author-name`

GET `/authors/:author-name`

GET `/authors (returns all authors)`

Sample response data from GET /authors/author1
```
{
	"author-name": "author1",
	"author-location": "Sydney"
}
```

Sample Authers data to start with:
```
author1,Sydney
author2,Melbourne
author3,Brisbane
```

## Acceptance Criteria:
1. API working
2. Error handling
3. Logging and unit tests
