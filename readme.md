- [x] Provision a VM with vagrant and mount a shared folder that has the "Jenkins Config" and the "Inventory" files.

- [x] Create two instances on AWS for an Agent machine and a JenkinsHost machine.

- [x] SSH inside the vagrant machine and rsync the shared folder from this machine, to the Agent machine by it's ubuntu ip address.

- [x] SSH inside the Agent machine and locate the folder that has been rsynced in

- [x] Locate the playbook files inside the shared folder required to run this project,

- [x] Make sure that you're in the directory for the shared folder and then run a command to run the playbook

- [x] ansible-playbook -v jenkins-config.yml -i inventory.txt

- [x] Once this command has run and is completed.

- [x] Use the public IP for the JenkinsHost machine and enter it into your browser, followed by the port access ":8080"

- [x] This will then load up the Jenkins app within the browser.

![Preview](./public/Preview.gif)
