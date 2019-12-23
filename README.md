# Docker Quorum

A role to join a Docker Swarm Manager to a Swarm as a memeber of the quorum.

## Example playbook

```yaml
- hosts: manager[1:]
  roles:
    - quorum
```
