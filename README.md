# zsh
Follow me as I try to make ansible setup my terminal enviroment

IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, 

IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README, IGNORE README,













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