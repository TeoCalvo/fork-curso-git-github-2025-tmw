# Curso Git & GitHub 2025 - Teo Me Why

Um curso para iniciantes em **Git** e **GithHub**, onde vocês podem aprender versionamento de código e repositórios remotos com GitHub,
inclusive **GitFlow** e **Visual Studio Code** ao final do curso.

Confira tudo no único canal que ensina sobre a Área de Dados de maneira gratuita:

## Teo Me Why

### **Youtube:** https://www.youtube.com/@teomewhy

(Playlist do Youtube - Introdução ao Git e GitHub - https://www.youtube.com/playlist?list=PLvlkVRRKOYFQyKmdrassLNxkzSMM6tcSL)

### **Twitch**: https://www.twitch.tv/teomewhy

(Coleções da Twitch - Git e GitHub 2025 - https://www.twitch.tv/collections/Ujre2jwtHxgN0w?filter=collections)

----

## Fluxo de trabalho Git local

1. git checkout -b nova_branch - Exemplo: git checkout -b secundaria  

2. criar ou alterar arquivos

3. git status

4. git add nome_do_arquivo - Exemplo: git add README.md

5. git status

6. git commit -m "nova mensagem" - Exemplo: git commit -m "mudança no README"

7. git checkout main - retornar para branch "main"

8. git merge nova_branch - unir informações da branch "secundaria" com a "main"

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)

01. git clone endereço_do_projeto - Aula "CRIANDO FORK", aos 3:22 do vídeo
02. git checkout -b nova_branch - Exemplo: git checkout -b secundaria
03. alterações de arquivos
04. git status
05. git add nome_do_arquivo - Exemplo: git add README.md
06. git status
07. git commit -m "nova mensagem" - Exemplo: git commit -m "mudança no README"
08. git push origin nova_branch - Exemplo: git push origin secundaria
09. abrir Pull Request para a "main", no GitHub - Aula "CRIANDO FORK", aos 8:49 do vídeo
10. excluir nova_branch origin - Aula "CRIANDO FORK", aos 18:20 do vídeo
11. git checkout main - retornar para branch "main"
12. git branch -D nova_branch - excluir branch pelo terminal - Exemplo: git branch -D secundaria

## Fluxo de trabalho GitHub <> Local (projetos open-source)
01. Fork do projeto para seu próprio GitHub
02. git clone endereco_do_projeto_fork - Exemplo: Aula "CRIANDO FORK", aos 3:22 do vídeo
03. git checkout -b nova_branch - Exemplo: git checkout -b secundaria
04. alterações de arquivos
05. git status
06. git add nome_do_arquivo - Exemplo: git add README.md
07. git status
08. git commit -m "nova mensagem" - Exemplo: git commit -m "mudança no README"
09. git push origin nova_branch - Exemplo: git push origin secundaria
10. abrir Pull Request da sua branch fork para a "main" do projeto original, no GitHub - Aula "CRIANDO FORK", aos 8:40 do vídeo
11. excluir nova_branch origin - Aula "CRIANDO FORK", aos 18:20 do vídeo
12. git checkout main - retornar para branch "main"
13. git branch -D nova_branch - excluir branch pelo terminal - Exemplo: git branch -D secundaria

----

Pessoas participantes:

- Igor Dammous
- Infoslack
- Leo Medeiros
- Magno Emanuel
- Mateus Dantasa
- Tales
- Téo Calvo