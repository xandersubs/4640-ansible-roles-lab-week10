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
## screenshot
<img width="861" height="286" alt="image" src="https://github.com/user-attachments/assets/2b2ef918-49c6-4320-b172-4434ba1b36a4" />

