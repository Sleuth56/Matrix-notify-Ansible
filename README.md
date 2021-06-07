# Matrix notify Ansible 
Utilizes [Fabianonline's matrix.sh scrypt](https://github.com/fabianonline/matrix.sh) to allow easy piping of files or whatever to a matrix room for logging.

## Prerequisite
1. Install [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
2. Install git

## Using Ansible pull
`sudo ansible-pull -U https://github.com/Sleuth56/Matrix_notify_Ansible.git`

## Usage
```echo 'Test' | matrixLog```
```date | matrixLog```
