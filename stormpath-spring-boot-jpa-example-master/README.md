#Stormpath is Joining Okta
We are incredibly excited to announce that [Stormpath is joining forces with Okta](https://stormpath.com/blog/stormpaths-new-path?utm_source=github&utm_medium=readme&utm-campaign=okta-announcement). Please visit [the Migration FAQs](https://stormpath.com/oktaplusstormpath?utm_source=github&utm_medium=readme&utm-campaign=okta-announcement) for a detailed look at what this means for Stormpath users.

We're available to answer all questions at [support@stormpath.com](mailto:support@stormpath.com).

# CRUD App with Spring Boot

This is the code developed in the tutorial (https://stormpath.com/blog/tutorial-crud-spring-boot-20-minutes) on creating a flexible CRUD app with Spring Boot.

It features full REST compliance and an embedded database.

### Requirementhls;s;l;slsksj

- Maven
- JDK 7

### Running

To build and start the server simply type

```sh
$ mvn spring-boot:run
```

from the root directory.

### Using

You can see what urls are available using curl:

```sh
$ curl localhost:8080
```

You can view existing people objects using a similar request:

```sh
$ curl localhost:8080/persons
```

and can create new ones using a POST:

```sh
$ curl -X POST -H "Content-Type:application/json" -d '{ "firstName" : "Karl", "lastName" : "Penzhorn" }' localhost:8080/persons
```

### Todo

 - Switching out database
 - Paging results
 - Writing tests

### License
----

MIT
yes this more important
