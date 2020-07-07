LA PRUEBA DE QUE SI FUNCIONA GIT
### Sharing & Updating Projects / Compartiendo y Repositorios Remotos

| Command | Description | Descripción |
| ------- | ----------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository | Envia el repositorio local a remoto |
| `git push origin --delete [branch name]` | Delete a remote branch | Elimina un repositorio remoto |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository | Hace un feth y fusiona
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository | Crea un repositorio remoto |
| `fork` | Copy a external repository | Copa un repositorio externo |
| `git remote -v` | list remote connections | Lista las conexiones remotas |
| `git remote set-url [branch name] [url]` | Change the url | Cambia la url del repositorio |

### Inspection & Comparison / Inspeccion y Comparacion

| Command | Description | Descripción |
| ------- | ----------- | ----------- |
| `git log` | View changes | Muestra los cambios en el repositorio |
| `git log --summary` | View changes (detailed) | Muestra los cambios en el repositorio detalladamente |
| `git log -all --graph --decorate --oneline` | View changes (Max-detailed) | Muestra todos los cambios del repositorio detallada y graficamente |
| `git diff [source branch] [target branch]` | Preview changes before merging | Compara los diferentes cambios |


### Others / Otros

| Command | Description | Descripción |
| ------- | ----------- | ----------- |
| `alias [name=] "command"` | Create a shorcut for a command | Crea un alias para llamar a un comando |
| `git tag -a [name] -m "message" [id/hashtag]` | Create a tag for a commit | Crea un tag de un commit en especifico |
| `git show-ref --tags` | List all tags | Lista los tags existentes |
| `git push --tags` | Push tags to your repository | Envia los tags al repositorio remoto |
| `git tag -d [name]` | Delete a tag | Elimina un tag en especifico |
| `git push origin :refs/tags/[name]` | Delete a tag from GitHub | Elimina un tag dentro de GitHub |
| `gitk` | Open GUI | Abre una interfaz grafica |
| `git cherry.pick [id]` | Take commit from other branches | Trae un commit especifico desde otra rama |
| `git grep -n [word]` | Search words in the proyect | Busca la palabra especificada en todo el proyecto |
