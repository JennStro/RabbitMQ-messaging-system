# RabbitMQ-messaging-system

[Install](https://www.rabbitmq.com/install-homebrew.html)  RabbitMQ server and start it, then you can start the programs. 

The programs Send sends a "Hello world" to Receive. NewTask takes in an argument and send this task to Worker, who work for a number of "." seconds given to NewTask. NewTask "..." will make Worker busy for 3 seconds. EmitLog takes in an argument and broadcast logs to ReceiveLogs. 
