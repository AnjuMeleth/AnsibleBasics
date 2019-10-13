ssh-keygen -t rsa
  148  ssh-copy-id root@45.76.96.139
  149  ssh root@45.76.96.139
  150  sudo apt-add-repository ppa:ansible/ansible 
  151  apt-get update
  152  sudo apt-get install ansible
  153  ansible --version
  154  sudo nano /etc/ansible/hosts
  155  cd /etc/ansible
  156  ansible -m ping all
  157  vi/etc/hosts
  158  vi /etc/hosts
  159  ansible -m ping all
