# Controlando as versões do código

## O que é o git?

É um sistema de controle de versões distribuído, utilizado para registrar o histórico de edições de arquivos.

## O que é o github?

É uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git.

## Primeiros passos:

	Baixando o git para Windows : https://git-scm.com/download/win

## Iniciando o Git e criando um commit:

- **git init:** cria um repositório dentro do diretório (pasta), esse repositório fica em uma pasta oculta onde as versões do código serão gerenciadas;
		
- **git add:** joga o arquivo para o staged.
		
	Obs: git add *: o * pega tudo o que foi modificado no diretório de trabalho e adiciona para o staged.

- **git commit -m "escrever mensagem":** gera um commit, o que quer dizer que por baixo dos panos "tira um print" das modificações feitas e salva. Quando isso acontece o status volta para unmodified.

	Obs: o -m é uma flag que permite colocar uma mensagem. Essa mensagem irá servir para divulgar o que aquele commit fez. 

- **git remote add origin caminho do repositório remoto:** Centraliza o código-fonte para os outros projetos, criando uma referência. Ou seja, o comando git remote add origin caminho do repositório remoto cria um novo controle remoto chamado origin localizado em caminho do repositório remoto. Depois de fazer isso, nos comandos push, é possível enviar para a origin em vez de digitar a URL ou caminho inteiro.

- **git push origin master:** empurra do repositório local para o remoto.

## Resolvendo conflitos

- **git pull origin master:** puxa as alterações do repositório remoto para o local.
 
