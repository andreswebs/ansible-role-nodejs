# ansible-role-nodejs

Ansible role to install Node.js.


## Role Variables

- `nodejs_version`: Set the Node.js version in the format `node_<major>.x`, e.g. default `node_16.x`


## Example Playbook

```sh
- hosts: servers
  roles:
    - role: andreswebs.nodejs
```


## Authors

**Andre Silva** [@andreswebs](https://github.com/andreswebs)


## License

This project is licensed under the [Unlicense](UNLICENSE.md).
