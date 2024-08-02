# OPTO Connect Horizontal Case Dispenser Adapter #

This adapter encapsulates the basic logic required to operate a HCD using commands from a WES.

### What is this repository for? ###

* This repository contains the Java code for the HCD functions
* Version: 0.0.1

### What is in the repository? ###
The adapter has a number of parts that are defined as packages in the repository.

Activator : Code that processes the RabbitMQ responses back from Kepware by querying the Kepware REST API and return the results to OPTO WES via the feedback topics.

API : Datatypes and messages exchanged with the Kepware.

Config : YML configuration processing and the AMQP configuration setup.

Correlator : Defines what kind of Feedback a rabbit message is.

Repository : Used for persistence (JPA does not work very well with MongoDB)

Translator : Converts OPTO WES messages to Kepware posts.

### How do I get set up? ###

* TBD

