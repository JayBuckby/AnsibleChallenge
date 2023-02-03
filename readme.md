# Provision a VM with vagrant and mount a shared folder that has the "Jenkins Config" and the "Inventory" files.

# Create two instances on AWS for an Agent machine and a JenkinsHost machine.

# SSH inside the vagrant machine and rsync the shared folder from this machine, to the Agent machine by it's ubuntu ip address.

# SSH inside the Agent machine and locate the folder that has been rsynced in

# Locate the playbook files inside the shared folder required to run this project,

# Make sure that you're in the directory for the shared folder and then run a command to run the playbook

# ansible-playbook -v jenkins-config.yml -i inventory.txt

# Once this command has run and is completed.

# Use the public IP for the JenkinsHost machine and enter it into your browser, followed by the port access ":8080"

# This will then load up the Jenkins app within the browser.

![Preview](./public/Preview.gif)
