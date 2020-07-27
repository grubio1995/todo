# README

Mini app (Lista de tarefas) desenvolvido durante processo seletivo na empresa AutoSeg


# Requisitos

* Git
* Ruby
* Rails
* SQLite3
* Yarn

# Preparação

<b>Clonar este repositório:</b>

```shell
git clone https://github.com/grubio1995/todo
```
<b>E seguir para diretório (acessar via prompt de comandos)</b>

```shell
cd todo
```
<b>Instalar a bundle</b>

```shell
bundle install
```
<b> Instalar todas as dependências do projeto </b>

```
yarn install --check-files
```
<b>Então rodar a migration</b>

```shell
rake db:migrate
```
<b> Após isso, iniciar o servidor </b>

```shell
rails s
```
<b> E então acesssar a aplicação no navegador: locahost:3000 </b>
