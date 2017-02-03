# Ansible: npm

Install and update npm packages

Available on Ansible Galaxy: [pgkehle.npm](https://galaxy.ansible.com/pgkehle/npm)

## Variables
```yaml
deploy_dir:     Required for where the base path lives
```

## Tags

```YAML
  tags:
    - install
    - upgrade
```

## Examples

```YAML

  - hosts: all
  
    vars:
      do_install:     true
      do_update:      true

    roles:
      - { role: pgkehle.npm }
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))

## For local development testing

```bash
rsync -av ~/code/ansible-npm/* ~/.ansible/roles/pgkehle.npm
```

