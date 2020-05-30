# Role: Packer

![Molecule Test](https://github.com/crgwilson/ansible-role-packer/workflows/Molecule%20Test/badge.svg)

Install [Hashicorp Packer](https://www.packer.io/). A tool for building machine images.

## Whats it do?

- Installs the `unzip` package (required to install packer)
- Downloads and installs Packer

## Role variables

Variables for this role are pretty self-explanatory and can be found [here](defaults/main.yml)

## Role testing

Testing this role can be done via [molecule](https://github.com/ansible/molecule) on CentOS, Ubuntu, and Debian.

To run the tests simply run:

```
molecule test
```

## Dependencies

N/A

