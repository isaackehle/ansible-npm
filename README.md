# Ansible Role - npm

Install and update npm packages

Available on Ansible Galaxy: [isaackehle.npm](https://galaxy.ansible.com/isaackehle/npm)

## Variables

```yaml
deploy_dir: Required for where the base path lives
```

## Tags

```YAML
  tags:
    - install
    - packages
    - upgrade
```

## Examples

```YAML

  - hosts: all
    vars:

    roles:
      - { role: isaackehle.npm }
```

## Linting

```bash
yamllint -c yamllint.yaml .
ansible-lint .
```

## License

MIT

## Author Information

Isaac Kehle
@isaackehle ([twitter](https://twitter.com/isaackehle), [github](https://github.com/isaackehle), [linkedin](https://www.linkedin.com/in/isaackehle))
