# Basic Celery Working with Python

This task.py shows how to celery working 

## Getting Started

I just created a simple tasks.py, it turned a additional result for us.
on terminal, we can use it with for-statement and see how celery works.

### Prerequisites

We need to install celery and rabbitmq-server 
```
### Process

Just run rabbitmq-server and celery
-for run: rabbitmq --> rabbitmq-server         celery --> celery worker -A tasks -l INFO

on the another terminal just add the function and for-statement.

-from tasks import add
-for i in xrange(10000):
     add.delay(i,i)

that's all. and see how to celery process running on terminal.
