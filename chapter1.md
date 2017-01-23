# Quota

The private quota of a project can be managed by cloud administrator only via command line using the following 

OpenStack command:

`# openstack quota set --cores <num_vcpus> --ram <memory_size> --instances <max_num_instances> --class <project_id>`

The private quota will be updated from Synergy after a few seconds without restart it.

This example shows how the private quota of the project prj\_a has been modyfied:

