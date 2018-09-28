# ansible
1. Setup Build Machine by installing JDK 1.8, Maven
  $ ansible-playbook buildsetup.yml 

2. Create EC2 machine
  $ ansible-playbook createEc2.yml --skip-tags add

3. Create EC2 machine & add an entry to dynamic hosts file
  $ ansible-playbook createEc2.yml 
