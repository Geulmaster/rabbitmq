# rabbitmq

> Playground

- hello-world
- task_queue - work queue -> each task is delivered to exactly one worker.
- publish_subscribe - deliver a message to multiple consumers.
- routing - subscribe only to a subset of the messages. For example, we will be able to direct only critical error messages to the log file:

> python receive_logs_direct.py warning error > logs_from_rabbit.log

> python receive_logs_direct.py info warning error

> python emit_log_direct.py error "Run. Run. Or it will explode."

- rpc - run a function on a remote computer and wait for the result. This specific service returns Fibonacci numbers.

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

---
