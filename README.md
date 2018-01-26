# web-db-inctances
Heat orchestration templates (HOT) for provisionning :

- Private network :         OS::Neutron::Net
- Private subnet :          OS::Neutron::Subnet
- Router :                  OS::Neutron::Router
- Router interface :        OS::Neutron::RouterInterface
- Security groups :         OS::Neutron::SecurityGroup
- Ports :                   OS::Neutron::Port
- Floating ip :             OS::Neutron::FloatingIP
- Floating ip association : OS::Neutron::FloatingIPAssociation
- Instances :               OS::Nova::Server

to turn an secure httpd php 5.6 web server instance with an mysql 5.6 dabase server on another instance.
