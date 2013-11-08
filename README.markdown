# puppetdb-tools

Those are tools to simplify queries to the puppetdb. Really crude as this point, no erreur checking, no help, and so on. It uses the puppetdb API (v3) to query the DB, so it's much faster than the puppet node tool. It only runs on the puppetdb itself for now. Written on python 2.6, it doesn't require external libraries.

* puppet-list-nodes will list all nodes with last facts dump and last report
* puppet-get-fact will get fact for all nodes
* puppet-node-status will get the same information than `puppet node status`, but much faster.

# Limitations
Too many to list
