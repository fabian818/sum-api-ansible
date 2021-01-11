# Sum Api Ansible

Ansible configuration project for Sum Api project.

## Getting Started

### Prerequisites

```
Ansible
```

### Installing

Get the bastion ip from the output of [Sum Api Terraform](https://github.com/fabian818/sum-api-terraform) and modify the 
`hosts` file.

## Deployment

```
ansible-playbook -i hosts site.yml
```

## Built With

* [Red Hat Ansible](https://www.ansible.com/)- Deployment and Server configuration tool

## Versioning

I use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/fabian818/sum-api-ansible/tags). 

## Authors

* **Fabian Peña** - *Initial work* - [fabian818](https://github.com/fabian818)

