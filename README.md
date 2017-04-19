# Simple server with simple REST API

Run the server with `sbt run`. The server will run on `localhost:8080`.

Use `curl` to access the 'api':

```bash
$ curl -s -X GET localhost:8080/health
{"persons":[{"id":1,"name":"niels","age":28},{"id":2,"name":"laura","age":29},{"id":3,"name":"allan","age":68},{"id":4,"name":"merete","age":67},{"id":5,"name":"asser","age":34},{"id":6,"name":"sofie","age":31}]}
```


