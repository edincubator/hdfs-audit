# hdfs-audit

hdfs-audit.log is the log file where HDFS stores all the interactions of users
with the system. This repository show how to harvest this log using Flume and
analyze it with Zeppelin notebook tool.

It includes two files:
* hdfs-audit.json: Zeppelin notebook file.
* flume.conf: Flume configuration file.

The purpose of this tool is to monitorize the usage of each dataset for providing
a detailed information to data providers.
