# Pluggit

We value having control over the code we deploy into production but we also believe on not reinventing the wheel so we decided to use a micro-framework as a base for our projects.

## Setup

Install [composer](https://getcomposer.org/) if you don't have it already installed and run:

```
composer require silex/silex "~2.0"
```

## Basics

## Foundations


## Services

### Authentication
@Todo

### Authorization
@Todo

### Cache
@Todo

Copy something similar to [this](https://github.com/moust/silex-cache-service-provider)

### Circuit Breaker
@Todo

### Domain Events
@Todo (Hilari)

Get the copy from the base libraries

<https://github.com/CMProductions/domain-events>

### Encryption
@Todo

### Environment
Loads environment variables from `.env` to `getenv()`, `$_ENV` and `$_SERVER` automagically

<https://github.com/vlucas/phpdotenv>

### Hashing
@Todo

### Logging
@Todo (Hilari)

Copy one of the different copies we have of the Monolog formatter

<https://github.com/CMProductions/logging>

### Monitoring
@Todo (Hilari)

Copy the classes from the base libraries

<https://github.com/CMProductions/monitoring>

### Queues
@Todo (Quim)

Copy the classes from the base libraries

<https://github.com/CMProductions/queues>

### Service Discovery
@Todo

### Session
@Todo

### Storage
@Todo (Hilari)

Store files into different filesystems: disk, s3, ...

<https://github.com/CMProductions/storage>

### Tasks
@Todo (Quim)

Copy the classes from the base libraries

<https://github.com/CMProductions/tasks>