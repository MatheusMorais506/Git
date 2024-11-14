# Criar projeto Git local e linkar a um projeto remoto *(navegar até a pasta desejado)
`git init`
`git add .`
`git commit -m "Initial commit"`
`git remote add origin https://username@bitbucket.org/username/nome-do-repositorio.git`
`git push -u origin master`

# Linkar um repositório remoto a um repositório local ja existente *(navegar até a pasta desejado)
`git remote add origin git@github.com:username/nome-do-repositorio.git`
`git branch -M main`
`git push -u origin main`

# Clocar repositorio remoto *(navegar até a pasta desejado)
`git clone LinkDoRepositorio`