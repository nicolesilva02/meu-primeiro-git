# Utilizando Git e GitHub
## O que é o Git?
O git é um sistema gratuito e de código aberto utilizado para controle de versões de códigos em desenvolvimentos de sites, aplicativos e sistemas
## O que é o GitHub?
GitHub é uma plataforma de armazenamento de repositórios Git. Nela os usuários podem criar os seus perfis e armazenar diversos repositórios.
A plataforma é mantida pela Microsoft e permite acesso gratuito, por meio de uma conta autenticada e também possui sua versão paga.
O GitHub é também muito utilizado por desenvolvedores para manter um portifolio de projeto online
`este é um trecho de código`
### Comandos do Git 
#### Inicializando o Repositório Local
`git init`
#### Renomeando a Branch Principal para main
`git branch -M main`
#### Para adicionar o nosso arquivo ao repositório 
`git add readme.md`
##### Para adicionar o repositório remoto
`git remote add origin https://github.com/nicolesilva02/meu-primeiro-git.git`
##### Para fazer a primeira Commit do projeto
`git commit -m "Primeira Commit do Projeto"`
 ##### Enviando o arquivo para o repositório remoto (GitHub)
 `git push -u origin main`
#### Adicionar o Autor do Projeto
`git config --global user.email "nicole.gabriela.002@gmail.com"`
`git config --global user.name "nicolesilva02"`