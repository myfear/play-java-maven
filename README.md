# play-java-maven
A simple demo project about how to use Playframework with Maven

It just has a "hello world reply" on http://localhost:9000/
And you can post a JSON object to http://localhost:9000/hello


##Run with

``mvn install play2:run``


``curl -X POST -H "Content-Type:application/json" -d '{"name": "John", "last": "Dow"}' http://localhost:9000/hello``

"Hello John"
