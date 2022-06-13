# My Macbook!

Ansible all the things.

## Prerequisites

Assuming this is a "blank" Macbook that you're starting with:

1. [Install 1Password](https://1password.com/downloads/mac/).
1. Enable the 1Password SSH Agent feature, and copy the specified config settings to ~/.ssh/config.
1. Run `xcode-select --install`. Go make a sandwich.
1. Run the [install script](https://gist.github.com/itstommymorgan/cf2707f6172f0ef5a9daa5c8602c12cc): `bash <(curl -s https://gist.githubusercontent.com/itstommymorgan/cf2707f6172f0ef5a9daa5c8602c12cc/raw/9f3902166b7bd6bdc25cb3dfd8e813395d360c52/my_macbook_install.sh)`

The install script will ask you to edit the local config file, to put in information that the main playbook is going to need but that can't necessarily be committed to source control reasonably.
