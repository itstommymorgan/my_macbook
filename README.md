# My Macbook!

Ansible all the things.

## Prerequisites

Assuming this is a "blank" Macbook that you're starting with:

1. Checkout a read-only copy of this repository in a temp directory.
1. `xcode-select --install`
1. `python3 -m ensurepip --upgrade`
1. `pip install ansible`
1. `ansible-playbook bootstrap.yml`

The bootstrap playbook prompts for a hostname and a GH token - provided with both it'll do the rest of the setup necessary to run the main playbook, including downloading a read/write copy of the repository.
