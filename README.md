# Sum Api Ansible

Ansible configuration project for Sum Api project.

## Getting Started

### Prerequisites

```
Ansible
```

### Installing

Put the private key tenpo-cl-dev-kp in the root of the project.
Get the bastion ip from the output of [Sum Api Terraform](https://github.com/fabian818/sum-api-terraform) and modify the 
`hosts` file.

## Deployment

```
ansible-playbook -i hosts site.yml
```

After the deployment you will be able to send requests to the elb deployed with [Sum Api Terraform](https://github.com/fabian818/sum-api-terraform) (elb dns also available on that project).

## Built With

* [Red Hat Ansible](https://www.ansible.com/)- Deployment and Server configuration tool

## Versioning

I use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/fabian818/sum-api-ansible/tags). 

## Authors

* **Fabian Peña** - *Initial work* - [fabian818](https://github.com/fabian818)

