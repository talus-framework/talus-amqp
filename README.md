Successfull talus-amqp start up logs will look as follows:

# docker logs talus-amqp

              RabbitMQ 3.6.6. Copyright (C) 2007-2016 Pivotal Software, Inc.
  ##  ##      Licensed under the MPL.  See http://www.rabbitmq.com/
  ##  ##
  ##########  Logs: tty
  ######  ##        tty
  ##########
              Starting broker...

=INFO REPORT==== 24-Apr-2017::16:13:10 ===
Starting RabbitMQ 3.6.6 on Erlang 19.2
Copyright (C) 2007-2016 Pivotal Software, Inc.
Licensed under the MPL.  See http://www.rabbitmq.com/

=INFO REPORT==== 24-Apr-2017::16:13:10 ===
node           : rabbit@talus-amqp
home dir       : /var/lib/rabbitmq
config file(s) : /etc/rabbitmq/rabbitmq.config
cookie hash    : A29nbOcU6biPt5u5N5Er8g==
log            : tty
sasl log       : tty
database dir   : /talus/data/rabbitmq/rabbit@talus-amqp

=INFO REPORT==== 24-Apr-2017::16:13:11 ===
Memory limit set to 9605MB of 24013MB total.

=INFO REPORT==== 24-Apr-2017::16:13:11 ===
Disk free limit set to 50MB

=INFO REPORT==== 24-Apr-2017::16:13:11 ===
Limiting to approx 1048476 file handles (943626 sockets)

=INFO REPORT==== 24-Apr-2017::16:13:11 ===
FHC read buffering:  OFF
FHC write buffering: ON

=INFO REPORT==== 24-Apr-2017::16:13:11 ===
Database directory at /talus/data/rabbitmq/rabbit@talus-amqp is empty. Initialising from scratch...

=INFO REPORT==== 24-Apr-2017::16:13:11 ===
    application: mnesia
    exited: stopped
    type: temporary

=INFO REPORT==== 24-Apr-2017::16:13:13 ===
Priority queues enabled, real BQ is rabbit_variable_queue

=INFO REPORT==== 24-Apr-2017::16:13:13 ===
Starting rabbit_node_monitor

=INFO REPORT==== 24-Apr-2017::16:13:13 ===
Adding vhost '/'

=INFO REPORT==== 24-Apr-2017::16:13:13 ===
Creating user 'guest'

=INFO REPORT==== 24-Apr-2017::16:13:13 ===
Setting user tags for user 'guest' to [administrator]

=INFO REPORT==== 24-Apr-2017::16:13:13 ===
Setting permissions for 'guest' in '/' to '.*', '.*', '.*'

=INFO REPORT==== 24-Apr-2017::16:13:14 ===
msg_store_transient: using rabbit_msg_store_ets_index to provide index

=INFO REPORT==== 24-Apr-2017::16:13:14 ===
msg_store_persistent: using rabbit_msg_store_ets_index to provide index

=WARNING REPORT==== 24-Apr-2017::16:13:14 ===
msg_store_persistent: rebuilding indices from scratch

=INFO REPORT==== 24-Apr-2017::16:13:14 ===
started TCP Listener on [::]:5672
 completed with 0 plugins.

=INFO REPORT==== 24-Apr-2017::16:13:14 ===
Server startup complete; 0 plugins started.

