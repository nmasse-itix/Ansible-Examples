# Advanced features/aspects of Ansible

This repository is a collection of playbooks showing advanced features or
aspects of Ansible.

## Current examples

[Variable evaluation order](variable-order.yaml): shows that Jinja placeholders
in the variable value are evaluated when used and not when defined.

[Select filter and search test](select-filter-and-search-test.yaml): shows how
to combine the `select` filter of Jinja with the `match`/`search` test of 
Ansible to filter a list.
