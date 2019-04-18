# Amazon Managed Streaming for Kafka (MSK)

## Authors

René Gómez Londoño - Ivan Salfati

## Table Of Contents

[Introduction](#introduction)

[Stream Processing](#stream-processing)

[Apache Kafka](#apache-kafka)

[Architecture](#architecture)

[Amazon Managed Streaming for Kafka](#amazon-managed-streaming-for-kafka)

[Conclusion](#Conclusion)

## Introduction

Digitalization and the web 2.0 has lead to multiple data sources with structured and unstructured data. But the problem doesn’t stop there, we have also created different specialized tools to store, query and analyse such data. The combination of more data sources and the need to get this data into diverse systems leads to a huge data integration problem. From the architectural point of view, the rise of event data have forced to change from _monolithic_ applications to more scalable systems with _Services Oriented Architectures_ (SOA) and more recently _Microservices_. 

When systems reach a critical level of dynamism we have to change our way of modelling and designing them. However, this also increase the complexity of the communication systems required to properly transport data from the multiple sources to the multiple target systems. Companies easily end up building webs of micro-services, which are difficult to manage, debug and maintain.

[![microservices](img/00-microservices-oldarchitecture.png)](https://www.confluent.io)


The appropriate systems architecture for this inherent dynamic nature of complex engineered systems is what is called event driven architecture, built around the production, detection, and reaction to events that take place in time. 

The aim of stream processing platforms as Apache Kafka is precisely provide the capacities to process events in _real time_. 
Furthermore, since Big Data applications are deployed on the cloud, it is also important to study how to deploy Kafka in such infrastructures. 

In this document, we explore some concepts behind stream processing, Apache Kafka and the cloud computing services provided to manage Kafka clusters in the Amazon cloud computing platform. We also present the typical architecture for Kafka solutions, the data abstraction and its importance in the whole Kafka’s ecosystem. At the end of the document we present the use cases and some real production architectures that evidence Kafka’s performance in companies like Twitter and Uber.



## Stream Processing

### Event centric design 
More than data stores, a company is an active process, continuously reacting and operating as events occur. In consequence, event centric design have emerged and with it event driven architectures, a design pattern built around the production, detection, and reaction to events that take place in real time ([Fowler 2017](#fowler-2017)). Companies are rethinking their business as a stream of events and how to respond to those events. This perspective lets companies to model what happens in their business as events: the sales, the orders, the customer experience and behavior are streams of events that again, model the operation of the business. They key is to detect such events, find relations between them and react in a proper manner. 

### Stream processing platform

Data stores somehow are based on the illusion of static data, using tables as the data abstraction. The *purpose of streaming platforms is to model change explicitly*, thinking in data flows and using a log as data abstraction. 

![streaming-platform](img/01-streaming-platform.png)


Both situations, data integration and events processing require new technological solutions. The data generated continuously by thousands of data sources that send data records (messages or events) simultaneously and normally in small sizes is called streaming data ([AWS 2018](aws-2018)). The ability to process/react in real time to messages/events is called stream processing. 


## Apache Kafka

Kafka is a distributing stream processing platform. Kafka is a publish/subscribe messaging system designed to solve the problem of managing continuous data flows. 

For this reason, Kafka clusters are part of the data processing architecture of  a lot of companies like LinkedIn, Yahoo!, Twitter, Netflix, Spotify, Uber and many more.

Kafka got its start as an internal infrastructure system at LinkedIn. According to Jay Kreps ([Narkhede et al. 2017](narkhede-2017)) Kafka tries to solve the problems related with handling _continuous flows of data_.

Lorem
- Lorem 1: 
- Lorem 2:

## Architecture

### Component 1


#### Component 1.1

The following code shows...

```yaml
component code
```

Lorem

#### Componen 1.2

Lorem


### Component 2

Lorem


## Managed Streaming for Kafka (MSK)

### Introduction

### Benefits

### Configure

### Example


## Conclusion

In this report we have described the foundations of Kafka and MSK architecture.. 

## Sources and further readings

- [Link 1](https://link.io/)
