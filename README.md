# tower-rhosp-inventory
Testing adding a simple host filter for a meta data value of tower. 

Modified 2 lines in default tower inentory script to filter on meta data tag called tower. 
Just if the tag exists

added new inventory script. 
added new inventory source - custom script
Added invironment variables to source
private: False
use_hostnames: True
host_filters: tower="true"

Also added clouds.yaml to /etc/openstack/clouds.yaml

Added meta data tag to instances called tower - value doesn't matter


