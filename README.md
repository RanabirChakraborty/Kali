# Kali
It's an automation tool using Ansible that fetches a list of JIRA issues and sends an email.

### How to play with it -

Update the below in `vars.yml` file
* Update your Jira personal token access. 
* Update the Jira query you want to run.
* Update email host, port and address.

Now you are good to go. Run the `email.yml` playbook, and you'll get an email just like a magic.
