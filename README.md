# zsh
Follow me as I try to make ansible setup my terminal enviroment

IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, 

IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README,






kindas based on - https://github.com/Lileso/the_black_pearl_ansible/blob/main/roles/nginx/tasks/main.yml



believe alot can be stolen from - https://levelup.gitconnected.com/getting-started-with-ansible-local-automation-of-windows-10-and-ubuntu-20-04-workstations-ffd03d7dc923


#Instalation
1. Python must be installed
2. python -m pip install --user ansible
3. winget install "openssh beta"

ansible-playbook -i inventory.yaml,  book.yaml



wsl --install -d ubuntu




- win_chocolatey:
    name: spotify
  become: yes
  become_user: Administrator
  become_method: runas


  win_chocolatey:
    name: officepro2013
  become: yes
  become_user: Administrator
  become_method: runas
  choco install spotify

  - name: Run the 'whoami' executable with the '/all' argument
  ansible.windows.win_command:
    cmd: whoami.exe /all