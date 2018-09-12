# heat-templates
The HOT templates are defined in YAML and follow the structure outlined below. The templates in this repository are specifically for the deployment of a Kubernetes cluster on Openstack (KILO).

```
heat_template_version: 2015-04-30

description:
  # a description of the template

parameter_groups:
  # a declaration of input parameter groups and order

parameters:
  # declaration of input parameters

resources:
  # declaration of template resources

outputs:
  # declaration of output parameters

conditions:
  # declaration of conditions
```