filtered-websocket charm
=======================

Install filtered-websocket to a juju managed host.  The current implementation is extremely simple and will only run a broadcast server over port 9000.

TODO:
  - configurable options for filter, port, and storage object
  - automatically reconfigure to handle pubsub when redis instances appear in the environment
