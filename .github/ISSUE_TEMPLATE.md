<!--

** Please read the guidelines below. **

Issues that do not follow these guidelines are likely to be closed.

1.  GitHub is reserved for bug reports and feature requests.

2.  Is this bug report or feature request for a supported OS? If not, it
    is likely to be closed.  See https://www.elastic.co/support/matrix#show_os

3.  Please fill out EITHER the feature request block or the bug report block
    below, and delete the other block.

-->

<!-- Feature request -->

**Describe the feature**:

<!-- Bug report -->

**Elassandra version**:

**Plugins installed**: []

**JVM version** (`java -version`):

**OS version** (`uname -a` if on a Unix-like system):

**Description of the problem including expected versus actual behavior**:

**Steps to reproduce**:

Please include a *minimal* but **complete** **recreation** of the problem, including
(e.g.) index creation, mappings, settings, query etc.  The easier you make for
us to reproduce it, the more likely that somebody will take the time to look at it.

 1.
 2.
 3.

**Please provide the following information:

* elassandra logs (logs/system.logs or /var/lib/cassandra/system.log)
* elasticsearch cluster state (curl http://localhost:9200/_cluster/state)
* cassandra schema (cqlsh>DESC KEYSPACE <your_keyspace>)
* cassandra gossip state (run: nodetool gossipinfo)

