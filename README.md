munin-plugins-rabbitmq
=======================

Overview
--------
This package contains a set of munin plugins useful for monitoring a
RabbitMQ server. They use the RabbitMQ management interface with is over
HTTP and therefore have a very light profile on the server.

See the [documentation](http://www.rabbitmq.com/management.html) on the
RabbitMQ management interface for more details on what it provides.

Status
------
Currently we have the following plugins:

- rabbitmq\_connections
  - Use the `/api/connections` API to gather connections usage and
    transfer rates

- rabbitmq\_messages
  - Use the `/api/overview` API to gather messages rates by type

- rabbitmq\_node
  - Use the `/api/nodes` API to gather memory, process, fd and socket usage

- rabbitmq\_objects
  - TODO

- rabbitmq\_queue\_
  - TODO

See the relevant POD documentation/man pages for more information on usage.

Licence
-------

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Author
------

Written by Michael Jeanson <michael.jeanson@isvtec.com> based upon
nagios-plugins-rabbitmq by James Casey <jamesc.000@gmail.com>.
