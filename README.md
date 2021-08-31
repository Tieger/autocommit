# 用法：
ansible-playbook -i hosts automount.yml
### 修改ansible 参数文件，关闭首次登陆check_ssh_key 
vim /etc/ansible/ansible.cfg
host_key_checking=False
