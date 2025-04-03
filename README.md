﻿# GitHub Flow Demo
1. Configure o branch main como base do projeto.
2. Crie branches temporários para desenvolver funcionalidades.
3. Faça alterações e commits no branch temporário.
4. Envie o branch para o GitHub e crie um Pull Request.
5. Após revisão e merge, delete o branch temporário:
Via GitHub: Clique em "Delete branch".
Via Linha de Comando:

git push origin --delete <nome-do-branch> git branch -d <nome-do-

branch>

6. Atualize o branch main localmente com:

git pull origin main
