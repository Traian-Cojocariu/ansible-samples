Inside playbooks dir there is a file called sample_playbook.yml which is a simple example of an ansible playbook and its main sections. Also, it contains other useful playbook ready to be launched (the variables should be customized according to the system or usage).

Inside roles dir there is a folder called sample_role which is a basic role created with the command "ansible-galaxy init sample_role". What the role does is a debug of a static message. It is triggered by the sample_playbook.yml. Also, it contains basic standalone roles to be used in a very modular way.

Inside examples dir there are YAML files which contain specific tasks. These files cannot be simply launched with the "ansible-playbook test.yml" command.
