# rabbit-cli
Simple CLI for Rabbit MQ

##  All there is for now:

You can push a new message (by routing key):
```
./bin/publish_message "amqp://garden:garden@localhost:5672" mytest.routing_key_thingy test_message
```

returns:
```
Publish Success: true
```