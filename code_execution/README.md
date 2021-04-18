# Overview

This directory houses sinks for code execution in Python. This includes the execution of both Python code and shell commands (both on the local macheine, and remotely via protocols like SSH).

# Outstanding Work

Below is a list of libraries with known code execution sinks, for which we still need to write exploit demos.

## SSH Libraries

- [paramiko](http://docs.paramiko.org/en/stable/api/client.html#paramiko.client.SSHClient)
- [pexpect](https://pexpect.readthedocs.io/en/stable/api/pxssh.html)
- [fabric](https://docs.fabfile.org/en/1.12.1/tutorial.html)
- [spur](https://pypi.org/project/spur/)
- [asyncssh](https://asyncssh.readthedocs.io/en/latest/)
- [ssh2-python](https://pypi.org/project/ssh2-python/)
- [twisted.conch](https://twistedmatrix.com/documents/current/conch/howto/conch_client.html)
- [trigger](https://trigger.readthedocs.io/en/latest/examples.html#execute-commands-asynchronously-using-twisted)
- [parallel-ssh](https://github.com/ParallelSSH/parallel-ssh)
- [scrapli](https://github.com/carlmontanari/scrapli)
- [redexpect](https://github.com/Red-M/RedExpect/blob/master/examples/run_whoami.py)
- [netmiko](https://pypi.org/project/netmiko/)