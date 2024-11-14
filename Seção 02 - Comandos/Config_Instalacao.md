# Instalação
Baixar e instalar o git incluindo o gitbash

# Configurar usuario e email git
`git config --global user.name "Digitar Nome aqui"`
`git config --global user.email Digitar@Email.com`

# Trocar editor do GIT
`git config --global core.editor "code-wait"` editor do visual code

# Verificar configurações realizadas
`git config --list`

# Configuração GitHub Chave SSH 
- Conexão da máquina com o GitHub
- No GitBash
    `ssh-keygen -t rsa -b 4096 -C "email@hithub.com" ` Para criar chave
    `ls -al ~/.ssh` Verificar chaves
    (eval `ssh-agent -s`)  Colocar o ssh-agent em execução
    `ssh-add ~/.ssh/id_rsa` Adicionar chave privada SSH ao agente ssh
    `cat ~/.ssh/id_rsa.pub` Para visualizar a chave pública

- No GitHub -> Usuario -> Settings -> SSH and GPG Keys -> New SSH key (copiar a chave PÚBLICA e color aqui) 