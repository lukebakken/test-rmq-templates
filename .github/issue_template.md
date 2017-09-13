Thank you for using RabbitMQ and for taking the time to report an issue.

*Important:* please first read the [documentation on how to contribute][../CONTRIBUTING.md] to be sure your issue shouldn't be discussed on the [mailing list][rmq-users] first.

In order for the RabbitMQ team to investigate your issue, the following *must* be provided:
  
- [ ] Erlang version
- [ ] RabbitMQ version
- [ ] RabbitMQ plugin version(s)
- [ ] Client library version (for all libraries used)
- [ ] Operating system, version, and patchlevel
- [ ] RabbitMQ, server and client application logs
- [ ] A *complete*, working code sample or terminal transcript that can be used to reproduce the issue. We can't stress enough how much this helps!

Running the [`rabbitmq-collect-env`][rmq-collect-env] script can provide most of the information needed. Please make the archive available via a third-party service and note that the script does *not* attempt to scrub any sensitive data.

[rmq-users]: https://groups.google.com/forum/#!forum/rabbitmq-users
[rmq-collect-env]: https://github.com/rabbitmq/support-tools/blob/master/scripts/rabbitmq-collect-env
