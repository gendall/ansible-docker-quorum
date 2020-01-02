# Docker Quorum

A role to join a Docker Swarm Manager to a Swarm as a memeber of the quorum.

## Usage

Include this role in a playbook using a [requirements.txt](https://galaxy.ansible.com/docs/using/installing.html#installing-multiple-roles-from-a-file) file.

### Example playbook

```yaml
- hosts: manager[1:]
  roles:
    - quorum
```

## Deployment

This role will be automatically built and deployed to [Ansible Galaxy](https://galaxy.ansible.com) when a [Semver](https://semver.org) tag is pushed to the repo.
