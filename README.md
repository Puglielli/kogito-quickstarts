# Kogito Quickstarts

[![CircleCI](https://circleci.com/gh/mswiderski/kogito-quickstarts.svg?style=svg)](https://circleci.com/gh/mswiderski/kogito-quickstarts)

A collection of quickstarts for Kogito that illustrates various uses case covered.

Since Kogito aims at supporting both Quarkus and SpringBoot each quickstart should provide both type of projects.

**To try it out locally on latest stable version download the released repository content [here](https://github.com/mswiderski/kogito-quickstarts/releases/latest)**

## Kogito hello world with scripts

shows most basic use of processes to build up a hello world example

* [on Quarkus](kogito-scripts-quarkus)
* [on SpringBoot](kogito-scripts-springboot)


## Kogito with business rules

shows integration between processes and rules.

* [on Quarkus](kogito-business-rules-quarkus)
* [on SpringBoot](kogito-business-rules-springboot)


## Kogito with Kafka

shows how message start and end events can be easily used to integrate with Apache Kafka to consume where
message name is the Kafka topic and the payload is mapped to process variable. Uses custom types
that are serialized into JSON.

* [on Quarkus](kogito-kafka-quickstart-quarkus)
* [on SpringBoot](kogito-kafka-quickstart-springboot)

## Kogito with Infinispan persistence

shows long running processes with Infinispan persistence so the state of process instances can
be preserved across service restarts.

* [on Quarkus](kogito-infinispan-persistence-quarkus)
* [on SpringBoot](kogito-infinispan-persistence-springboot)

## Kogito with service invocation

shows how easy it is to use local services to be invoked from within process. Allows easy and readable
service invocation use cases to be covered.

* [on Quarkus](kogito-service-calls-quarkus)
* [on SpringBoot](kogito-service-calls-springboot)

## Kogito with REST call

shows REST service invocation and parsing data back to an object instance used as process variable.

* [on Quarkus](kogito-service-rest-call-quarkus)
* [on SpringBoot](kogito-service-rest-call-springboot)

## Kogito with user tasks

shows user task interactions with four eye principle applied

* [on Quarkus](kogito-usertasks-quarkus)
* [on SpringBoot](kogito-usertasks-springboot)

## Kogito with user tasks based on custom life cycle

shows user task interactions with four eye principle applied that supports custom life cycle that allows to
add additional phases to user tasks to indicate other states.

* [on Quarkus](kogito-usertasks-custom-lifecycle-quarkus)
* [on SpringBoot](kogito-usertasks-custom-lifecycle-springboot)

## Kogito with user tasks with security on REST api

shows user task interactions with four eye principle applied with security restrictions on REST api.

* [on Quarkus](kogito-usertasks-with-security-quarkus)
* [on SpringBoot](kogito-usertasks-with-security-springboot)

## Kogito with timers

shows timers (intermediate and boundary) that allows to introduce delays in process execution

* [on Quarkus](kogito-timer-quarkus)
* [on SpringBoot](kogito-timer-springboot)

## Kogito with user tasks and prediction service

user tasks combined with prediction service (machine learning backed by SMILE project) that allows automate human centric workflows

* [on Quarkus](kogito-usertasks-with-predictions-quarkus)
* [on SpringBoot](kogito-usertasks-with-predictions-springboot)

## Kogito with Apache Camel

shows use of Apache Camel as the backend of service task to allow any kind of integration being done with numerous components of 
Apache Camel

* [on Quarkus](kogito-service-camel-quarkus)
* [on SpringBoot](kogito-service-camel-springboot)

## Kogito with Validation API

shows use of Validation API with combination of Kogito generated REST api. Allows to annotate with validation constraints 
data model which will then be enforced on the REST api level

* [on Quarkus](kogito-validation-quarkus)
* [on SpringBoot](kogito-validation-springboot)


## Contribution

Everyone is encouraged to contribute to this quickstarts by

* trying it out and providing feedback and ideas for improvement
* create new quickstarts
* blogging about it
* using it on conferences and workshops
