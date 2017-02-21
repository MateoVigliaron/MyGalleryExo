# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# MyGalleryExo

# TP POPSCHOOL LENS RAILS

## 1/ On crée l'application

 - en  précisant la base de données avec l'option  **-d mysql **

```shell
$ rails new MyGallery -d mysql
$ cd MyGallery
```

## 2/ on crée le dépôt git et on le configure si besoin
```shell
$ git init .
$ git config --local user.email "dd@pop.eu.com"
```

## 3/ **On oublie pas** de protéger son fichier de configuration à la base de données
- L'idée et de se le garder pour le bon fonctionnement de l'application et de laisser un modèle dans le dépôt.


```shell
$ echo 'database.yml' > .gitignore
$ cp config/database.yml config/database.yml.sample
```

## 4 On crée le dépôt

Je vous laisse créer un dépôt **public** sur framagit, github ou autre.

## 5  add / commit / push

```
$ git add .
$ git commit -m 'initial commit'
$ git remote add origin git@framagit.org:daviddemonchy/MyGallery.git
$ git push -u origin master
```
