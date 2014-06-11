# Ansible GitLab

A basic Ansible playbook to install GitLab on Ubuntu.

## Usage

First, update the **ansible_hosts** file to include the nodes to be provisioned. A single entry has been provided by default for deployment using Vagrant. You will just need to update the IP address corresponding to your Vagrant instance.

Once the nodes have been added to the hosts file, run the playbook to install GitLab.

    $ ansible-playbook deploy.yml

When the playbook has finished successfully, fire up a web browser and type in the IP address for the instance. The GitLab login page should be displayed.

Type in the default credentials to get started.

    Username: root
    Password: 5iveL!fe

You be prompted to change the default password the first time you log in.
