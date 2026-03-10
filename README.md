# 4640-ansible-roles-lab
## AWS Key connection
### Keygen command
```bash
ssh-keygen -t ed25519 -f ~/.shh/aws
```
### importing the key
```bash
chmod+x import_lab_key
./import_lab_key ~/.ssh/aws.pub
```
## Terraform Initalization
```bash
terraform init 
terraform plan
terraform apply
```
## Running Ansible
### Verify dynamic inventory is working
```bash
ansible-inventory --graph
```
### Run the full playbook
```bash
ansible-playbook playbook.yml
```
