# Skyport 4 Work Log

Pohsun Huang(pohsun@infinitiessoft.com)

Tata Chen(tata@infinitiessoft.com)

we have decided to keep a record of our work on Skyport 4 here in the repo. It can be removed when the project goes live, but will serve as a handy log of what I'm doing and thinking during development.

### TODO

* add console apis
* in memory cache
* add cors filter
* add javascript ui by openstack api
* object storage(swift) api
* add testcases

### Work in process

* testcases for swift1.0-api, nova2.0-api modules.

### 22th March 2016

* add testcases to swift1.0-api, nova2.0-api modules.

### 9th March 2016

* integrate nova2.0-api, neutron-api with openstack-api-commons
* add swift1.0-api modules : account-metadata, container-metadata, object-metadata

### 8th March 2016

* integrate nova2.0-api, neutron-api with openstack-api-commons
*  add swift1.0-api modules : copy-object, create-object, delete-object

### 4th March 2016

* add openstack-api-commons modules
* add swift1.0-api modules : list-container, list-object, create-container, delete-container

### 3th March 2016

* integrate jersey with spring-mvc, spring-data.
* add neutron2.0-api module.
* investigate yellow circle, trystack.

### 2th March 2016

* integrate jersey with spring-mvc, spring-data.
 
### 1th March 2016

* integrate jersey with spring-mvc, spring-data.
* nova2.0-api resource : networks, subnets, ports.
 
### 26th February 2016

* add nova2.0-api resource : os-interface.
* add networkinterface support in cloud-openstack.
* Wrtie the Openstack Driver Usages of implemented api : os-interface.
* update ExceptionWrapper
* add Update Server api

### 25th February 2016

* add nova2.0-api resource : os-networks, os-interface.
* Wrtie the Openstack Driver Usages of implemented api : os-networks, os-interface.

### 24th February 2016

* add nova2.0-api resource : os-snapshots, os-keypairs, os-security-groups, os-security-group-rules.
* Wrtie the Openstack Driver Usages of implemented api : os-snapshots, os-keypairs, os-security-groups, os-security-group-rules.

### 23th February 2016

* add nova2.0-api resource : os-volume_attachments, os-volumes.
* Wrtie the Openstack Driver Usages of implemented api : os-volumes.
* openstack add loadbalancer ,listener, member

### 22th February 2016

* add skyport-core network service implements : vlan, loadbalancer
* add skyport-api network proxy : vlan, subnet, loadbalancer

### 19th February 2016

* Refactor nova2.0-api and wrtie the Openstack Driver Usages of implemented api : versions, limits, availability zone
* add nova2.0-api resource : os-availability-zone, os-volume_attachments
* add skyport-core : cached network service

### 18th February 2016

* Refactor nova2.0-api and wrtie the Openstack Driver Usages of implemented api : server_ips, server_metadata, image_metadata.
* add nova2.0-api resource : loadbalancers

### 17th February 2016

* Refactor nova2.0-api
* Move keystone middleware code to keystone4j-client 
* wrtie the Openstack Driver of implemented api: servers, servers_action, flavors, images, networks.
* add nova2.0-api : networks, subnets
