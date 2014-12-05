# ansible-accumulo

An Ansible role for installing [Apache Accumulo](https://accumulo.apache.org/).

## Role Variables

- `accumulo_version` - Accumulo version.
- `accumulo_mirror` - A mirror for the Accumulo packages (default: `http://www.webhostingjams.com/mirror/apache`)
- `accumulo_conf_dir` - Configuration directory for Accumulo (default: `/etc/accumulo/conf`)

## Example Playbook

See the [examples](./examples/) directory.
