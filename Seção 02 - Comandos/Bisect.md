# Bisect (Identificar em qual commit começou a ocorrer um problema)
* ordem de comandos:

`git bisect start`
`git bisect good hashCommit`
`git bisect bad hashCommit`
`git bisect good` (quando achar um commit quer esta ok)
`git bisect good` (se identificar um commit com o erro)
`git bisect bad`