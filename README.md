# Demo playbook project

Use this playbook to create demo site for Antora trial.

## Install Antora

[Antora Installation Instructions](https://docs.antora.org/antora/2.0/install/install-antora/)

## Build Site

### To use the remote content repos

run:

`antora antora-playbook.yml`

To rebuild after remote content changes:

`antora --fetch antora-playbook.yml`

### To build from local changes

1. clone the demo content repos:

- `git@github.com:ricklarsen/quickstart-docs-demo.git`
- `git@github.com:ricklarsen/using-docs-demo.git`

1. Edit the `local-playbook.yml` file to point to the directories containing the cloned content.

1. Run `antora local-playbook.yml`

## Open Site in Browser

Find files in `build/site` directory.

