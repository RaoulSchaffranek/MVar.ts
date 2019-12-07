# MVar

[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=RaoulSchaffranek_MVar&metric=coverage)](https://sonarcloud.io/dashboard?id=RaoulSchaffranek_MVar)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=RaoulSchaffranek_MVar&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=RaoulSchaffranek_MVar)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=RaoulSchaffranek_MVar&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=RaoulSchaffranek_MVar)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=RaoulSchaffranek_MVar&metric=security_rating)](https://sonarcloud.io/dashboard?id=RaoulSchaffranek_MVar)

An MVar represents a shared, mutable variable. It can be thought of as an asynchronous first-in-first-out-queue, where `put` queues values and `take` takes values out of the queue. MVars are usefull to synchronize read- and write-operations on shared variables between concurrent tasks.

## Installation

MVar is available as a npm-package.

~~~bash
npm i mvar
~~~