# Creates user and copy ssh public key

## Configuration

- `user` user name to create
- `copy_local_key` path to public key - defaults current user `id_rsa.pub`

## Run

````shell
ansible-playbook playbook.yml -l host -u root
````
