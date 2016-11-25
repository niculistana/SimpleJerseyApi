# Simple Jersey API

I made this repository because I wanted a backend that is not made in a full-stack development platform Rails, Django, or PHP.
So I found an alternative using JAVA using a framework called Jersey.

# Getting started

Run the following commands, you are welcome to add your own shell script that can execute it in one command.
These instructions are based on Jersey's [Getting Started Guide](https://jersey.java.net/documentation/latest/getting-started.html#new-from-archetype).
```
git clone git@github.com:niculistana/simple_jersey_api.git
cd simple_jersey_api
mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-grizzly2 \
-DarchetypeGroupId=org.glassfish.jersey.archetypes -DinteractiveMode=false \
-DgroupId=com.example -DartifactId=simple-service -Dpackage=com.example \
-DarchetypeVersion=2.24.1
mvn clean test
mvn exec:java
```
Then navigate to http://localhost:8080/myapp/myresource to view your app running.

### Purpose
This repository is meant to provide the following:

- JSON payloads using endpoints using `org.json`. [[Documentation](http://www.docjar.com/docs/api/org/json/JSONObject.html)]
- Ease of endpoint resource development using [Jersey](https://jersey.java.net/).
- Endpoint testing using assertions.
- **More importantly**, Encourage people to separate front-end from their backend since JSON, microservices, and APIs, are becoming 
[more and more apparent](https://www.google.com/trends/explore?q=json,microservices,api) in the industry.

### Disclaimer

I still am learning how to develop quick backends in JAVA, so the development of this repo could be opinionated. But the main goal
here is to provide a fast way to scaffold a backend in JAVA without too many dependencies. Please check out **Purpose** above to review
the repository's goals.

### Development
I currently work full-time and could continue support on the development of this repository as I see fit. For now, there wouldn't be much
developments that are going on since the repository already serves the purpose. I could make a fork of it to give it various flavors.
Feel free to fork your own as well, and I'd add a link to it in this repository so that others could see it. I may also add a Spring
alternative to those who are comfortable with [Spring](https://projects.spring.io/spring-framework/) once I get a chance to learn it.

### Forks to be implemented in the future
- Simple Jersey API w/ Oracle (no view)
- Simple Jersey API w/ Couchbase (no view)
- Simple Jersey API w/ React/Redux (no store)
- Simple Jersey API w/ Unity3D (no store)

For reference: 
- **store** = database or anything that saves the state,
- **view** = anything that presents the state via a UI.

### Contact
Feel free to send me a message via [@apebeast](https://twitter.com/apebeast).