`git branch NomeDaBranch` Criar nova branch
`git checkout NomeDaBranch` Acessar nova branch criada e sair da branch principal (master)
`git checkout master` Voltar para branch principal(master)
`git branch` Visualizar todas as linhas do tempo(branch)
`git merge NomeDaBranch` Unir outras branchs a branch principal(master)
`git branch -D NomeDaBranch` Deletar branch
`git branch -m NomeDaBranch` Renomear branch atual, obs: antes de renomear excluir a branch do repositorio remoto e depois subir de novo
`git branch -a`Listar modificações remotas
`git push -u <remote> NomeDaBranch>` Enviar nova branch para repositorio remoto
`git checkout -b NomeDaBranch` Criar nova branch e mudar para ela ao mesmo tempo
`git reflog --all | grep NOME_BRANCH` Saber a branch de origem de uma nova branch
`git checkout 393109e -- arquivo.js`Recuperar arquivo (OBS:393109e numero do commit que vai ser recuperado (verificar com 'git log'))
`git switch –C nomeBranch` Trocar/criar branch
`git push --set-upstream origin nomeBranch` Subir branch local para repositorio remoto
`git push -d nomeBranch` Remover branch local
`git push –delete origin nomeBranch` Remover branch remota, ao fazer isso também remover a local
`git branch --no-merged` Descobrir branchs que não receberam merge
