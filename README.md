# playbook-to-install-wordpress-on-LAMP-or-LEMP

-first:
put remote machines IPs in your inventory file 

-second:
put the value of stack varaible in front of your machine IP to be lamp or lemp

-third 
run the ansibe command as:
ansible-playbook -u root -k lamp_lemp.yml -i inventory 
 
