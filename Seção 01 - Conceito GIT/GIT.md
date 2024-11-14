# O que é GIT
    - Sistema de controle de versão distribuído
    - Open-source
    - Sistema de commit(viagem no tempo)
        - Histórico de alterações no código
        - Voltar para qualquer ponto na história
    - Controle de novas funcionalidades(universos paralelos)
        - Ramificações: branch
        - Vários devs no mesmo projeto
        - Análise e resolução de conflitos

# Controle de Versão
    - Controla as modificações feitas no projeto criando uma nova versão
    - Possível reverter o estado do arquivo a um determinado tempo arterior
    - linha do tempo das modificações
    - Comparar mudanças dos arquivos ao longo do tempo
    - Verificar usuário que realizou determinada modifição
# Tipos de Controle de Versão
<SistemaLocal>
    - copiar arquivos para outro diretório
    - Comum e simples
    - Propenso a erros
    - Fácil em sobreescrever arquivos
<SistemaCentralizado>
    - Exemplos: CVS, Subversion, Perforce
    - Disponível em um único servidor que contém todos os arquivos
    - Clientes usam arquivos desse servidor
    - Controle de administração
    - Perda total em caso de disco rígido corrompido
    - Servidor ao cair impossibilita o salvamentos das alterações.
<SistemaDistribuído>
    - Exemplos: <Git>, Mercurial, Bazaar, Darcs
    - Duplicar(clonar) localmente o repositório completo
    - Cada clone é um backup completo de todos os dados
    - Clientes usam o estado mais recente dos arquivos

# Branch (Nova linha do tempo)
- Uma ramificação no git é um ponteiro para as alterações feitas nos arquivos do projeto. É útil em situações nas quais você deseja adicionar um novo recurso ou corrigir um erro, gerando uma nova ramificação garantindo que o código instável não seja mesclado nos arquivos do projeto principal. Depois de concluir a atualização dos códigos da ramificação, você pode mesclar a ramificação com a principal, geralmente chamada de master.
- Modifica arquivos sem alterar o branch Principal (master)
- Possibilita muitas pessoas trabalhando no mesmo projeto, cada uma em uma determinada branch

# Git Worflow
    - Local Repository
    - Stage Area
    - Working Directory

# Hash Values (SHA-1)
    - checksum - converte dados em numero

# Head
    - Aponta em que ponta da história se esta

# GITIGNORE - Ignorar arquivos e diretórios indesejados
` Arquivo gitignore`
    Ignorar arquivos para não subirem no diretório 
    Criar arquivo .gitignore
    ` git rm -r --cached .` remover cash
    ` git add .gitignore `
    ` git commit -m "add .gitignore" `