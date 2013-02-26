modules/dist/github
===================

This is a puppet module that install the Github host key into the system known
hosts file (typically /etc/ssh/ssh_known_hosts).  Including the github class
from this module in a puppet node will allow git activity on the node to
proceed without ever having to answer whether to trust the host key while
maintaining secure authentication of the Github server.
