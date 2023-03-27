# My Macbook!

Ansible all the things.

## Prerequisites

Assuming this is a "blank" Macbook that you're starting with:

1. [Install 1Password](https://1password.com/downloads/mac/).
1. (Optional but helpful) Enable the biometric login, both in general AND for
   the 1password CLI.
1. Enable the 1Password SSH Agent feature, and copy the specified config settings to ~/.ssh/config.
1. Run `xcode-select --install`. Go make a sandwich.
1. Clone the install script: `git clone
   https://gist.github.com/cf2707f6172f0ef5a9daa5c8602c12cc.git ~/install-script`
1. Run the install script: `bash ~/install-script/my_macbook_install.sh`

The install script will ask you to edit the local config file, to put in information that the main playbook is going to need but that can't necessarily be committed to source control reasonably.
