![](https://wac-cdn.atlassian.com/dam/jcr:c942540c-53ae-4357-bffa-ed37739d71b0/bitbucket-atlassian-logo.svg?cdnVersion=431)
<p align="center" width="100%">
  <img width="33%" src="https://blog.4linux.com.br/wp-content/uploads/2018/01/Heroku-1900x802_c.png" />
</p>

# Teste Revert Bitbucket 
## com Bitbucket-pipeline e heroku


Está é uma das docs sobre o [Bitbucket-pipeline](https://support.atlassian.com/bitbucket-cloud/docs/deploy-to-heroku/); tem muita informação sobre o assunto.  

Aqui voce encontra uma breve descrição de como usar o [Heroku](https://share.atelie.software/subindo-um-site-simples-para-o-heroku-7450592106c8) bem simples.  

Site para criar um [Email temporário](https://temp-mail.org/pt/) e fazer o cadastro no Bitbucket e no Heroku

## Aqui vamos ver um de uma forma simples o processo no Bitbucket que consiste em:
```
[  ] - criar uma conta no heroku
[  ] - criar os app a serem usados( no Heroku )
[  ] - criar uma APIKEY a ser usada no deploy
[  ] - criar uma conta no Bitbucket
[  ] - criar um repositorio no Bitbucket
[  ] - altera a branch principal para main
[  ] - criar a branch develop
[  ] - configurar as branchs
[  ] - Configurar bitbucket para rodar pipeline
[  ] - fazer o clone
[  ] - criando uma feature
[  ] - fazer alterações
[  ] - subir PR
[  ] - fazer o merge em develop
[  ] - criar uma release partindo da branch develop
[  ] - criar uma PR da release para a main
[  ] - fazer o merge
[  ] - altera a feature
[  ] - criar nova PR
[  ] - Merge na Develop
[  ] - fazer o merge
[  ] - criar uma release partindo da branch develop
[  ] - criar uma PR da release para a main
[  ] - fazer o merge
[  ] - fazer o REVERT no bitbucket para a branch main
[  ] - altera a feature
[  ] - criar nova PR
[  ] - Merge na Develop
[  ] - fazer o merge
[  ] - criar uma release partindo da branch develop
[  ] - criar uma PR da release para a main
[  ] - resolver conflito
[  ] - fazer o merge
```