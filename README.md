## This task is to run simple http service over a remote EC2
- starting from installing the required tools
- copying required files
- start the service 

## using bash to run this play book
```bash
 ansible-playbook main-remote.yml -i inventory --private-key=../us-west-1.pem
```
taking into consideration `-i inventory` contains the address for the remote host
and `--private-key=../us-west-1.pem` is the private key to connect to this remote host
