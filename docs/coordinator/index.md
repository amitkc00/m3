# M3 Coordinator, API for reading/writing metrics and M3 management

M3 Coordinator is a service that coordinates reads and writes between upstream systems, such as Prometheus, and downstream systems, such as M3DB. 

It also provides management APIs to setup and configure different parts of M3.

The coordinator is generally a bridge for read and writing different types of metrics formats and a management layer for M3.
