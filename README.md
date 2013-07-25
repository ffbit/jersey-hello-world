This an application example from [Jersey's official tutorial](https://jersey.java.net/documentation/latest/getting-started.html)

It can be tested by

    mvn clean test

It can be run by

    mvn clean package exec:java

And **can't** be accessed on the declared URL: http://localhost:8080/myapp/myresource

**Note**<br />
In spite of the fact that it prints a lot of stack trace it still works somehow.
