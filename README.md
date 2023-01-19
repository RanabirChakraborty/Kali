# Kali
It's an automation tool using Ansible that fetches a list of JIRA issues and sends an email.

### How to play with it -

* Update the `vars.yml` file with your Jira personal token access and also change the email recipient.
* Update the Jira query you want to run.

Now you are good to go. Run the `email.yml` playbook, and you'll get an email just like a magic.
