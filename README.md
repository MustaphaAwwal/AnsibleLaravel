# AltschoolExam
This is my Exam repository, to deploy laravel and its dependencies using ansible from a control node to slave node
## To deploy from a control node and to a slave machine
* Clone this Repository
* Set the slave node ip address in the hostname file
* Set the mysql variable in the mysql/vars/main.yml
* run `ansible-playbook assignment.yml` to deploy
