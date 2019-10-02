# Ansible Role - npm

Install and update npm packages

Available on Ansible Galaxy: [pgkehle.npm](https://galaxy.ansible.com/pgkehle/npm)

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
      - { role: pgkehle.npm }
```

## Linting

```bash
yamllint -c yamllint.yaml .
ansible-lint .
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
