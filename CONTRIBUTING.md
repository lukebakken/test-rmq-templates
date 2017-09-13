Thank you for using RabbitMQ and for taking the time to contribute to the project.

# Overview

## GitHub issues

Team RabbitMQ uses GitHub issues for _specific actionable items_ engineers can work on. This assumes the following:

* GitHub issues are not used for questions, investigations, root cause analysis, discussions of potential issues, etc (as defined by this team)
* We have a certain amount of information to work with

We get at least a dozen questions through various venues every single day, often quite light on details. At that rate GitHub issues can very quickly turn into a something impossible to navigate and make sense of even for our team. Because of that questions, investigations, root cause analysis, discussions of potential features are all considered to be [mailing list][rmq-users] material by our team. Please post this to rabbitmq-users.

Getting all the details necessary to reproduce an issue, make a conclusion or even form a hypothesis about what's happening can take a fair amount of time. Our team is multiple orders of magnitude smaller than the RabbitMQ community. Please help others help you by providing a way to reproduce the behavior you're observing, or at least sharing as much relevant information as possible on the [mailing list][rmq-users]:

* Versions of the following:
    * Operating system (distribution as well)
    * RabbitMQ server
    * All client libraries used
    * RabbitMQ plugins (if applicable)
* Server logs
* A code example or terminal transcript that can be used to reproduce
* Full exception stack traces (not a single line message)
* `rabbitmqctl status` (and, if possible, `rabbitmqctl environment` output)
* Other relevant details about the environment and workload, e.g. a traffic capture
* Feel free to edit out hostnames and other potentially sensitive information.
* As an alternative, the [`rabbitmq-collect-env`][rmq-collect-env] script will collect all of this information (and more). Please note that no effort is made to scrub any information that may be sensitive

## Pull Requests

RabbitMQ projects use pull requests to discuss, collaborate on and accept code contributions. Pull requests is the primary place of discussing code changes.

# How to Contribute

The process is fairly standard:

 * Fork the repository or repositories you plan on contributing to
 * Clone the [RabbitMQ umbrella repository][rmq-umbrella-repo]
 * Run `make co` in the cloned umbrella repository to fetch dependencies into `deps/`
 * Create a branch with a descriptive name in the relevant repositories in `deps/`
 * Make your changes, run tests, commit with a [descriptive message][git-commit-msgs], push to your fork
 * Submit pull requests with an explanation what has been changed and **why**
 * Submit a filled out and signed [Contributor Agreement][ca-agreement] if needed (see below)
 * Be patient. We will get to your pull request eventually

If what you are going to work on is a substantial change, please first ask the core team for their opinion on [RabbitMQ mailing list][rmq-users].

# Code of Conduct

See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).

# Contributor Agreement

If you want to contribute a non-trivial change, please submit a signed copy of our [Contributor Agreement][ca-agreement] around the time you submit your pull request. This will make it much easier (in some cases, possible) for the RabbitMQ team at Pivotal to merge your contribution.

# Where to Ask Questions

If something isn't clear, feel free to ask on our [mailing list][rmq-users].

[rmq-collect-env]: https://github.com/rabbitmq/support-tools/blob/master/scripts/rabbitmq-collect-env
[rmq-umbrella-repo]: https://github.com/rabbitmq/rabbitmq-public-umbrella
[git-commit-msgs]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
[rmq-users]: https://groups.google.com/forum/#!forum/rabbitmq-users
[ca-agreement]: https://github.com/rabbitmq/ca#how-to-submit

# Project-specific contributing guidelines
