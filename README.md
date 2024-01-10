# ansible role template

[![Hope](https://img.shields.io/badge/tested%20by-H%C2%AF%5C__(%E3%83%84)__%2F%C2%AFPE-green.svg)](http://www.hopedrivendevelopment.com)

Minimal template for GarlicLabs: ansible roles.  
You can either generate default roles or roles for kubernetes, then a k3d setup in github action for molecule tests will be added and [pluto](https://github.com/FairwindsOps/pluto) deprication checks.  

## Setup

1. Install [pipx](https://github.com/pypa/pipx)
2. Install [copier](https://copier.readthedocs.io/en/stable/) via pipx

```bash
pipx install copier
```

## How to use

As easy as copier is.  

```bash
copier copy https://github.com/GarlicLabs/ansible_role_template ./
```

## Development

To bring the changes live you have done, create a tag and push it!   

## License

GNU General Public License version 3
