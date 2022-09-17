#  Backend for HEI admin

This project both specifies the
[HEI Admin API](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/hei-school/hei-admin-api/dev/doc/api.yml)
and implements it in Java.

[Releases](https://github.com/hei-school/hei-admin-api/releases) are published [here](https://gallery.ecr.aws/q6i6y5o4/hei-admin-api) as Docker images. Feel free to use them.

We welcome [contributions](https://github.com/hei-school/hei-admin-api/blob/dev/CONTRIBUTING.md).

## Necessary installation to execution  Hei_admin:

- Download [JDK](https://www.oracle.com/java/technologies/downloads/#java18) and install [JDK](https://www.youtube.com/watch?v=IJ-PJbvJBGs)
- Install [Maven](https://www.youtube.com/watch?v=RfCWg5ay5B0&t=1s)
- Install [Docker](https://docs.docker.com/desktop/install/windows-install/)
- Set [java_home](https://www.youtube.com/watch?v=104dNWmM6Rs) in environement variable
-  [Download postgresql](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads) and [install postgresql](https://www.youtube.com/watch?v=RAFZleZYxsc)to create a database "hei_amdin"

## Necessary installation for React:

```bash
npm i react-router-dom
```
```bash
npm i react-webcam
```
```bash
npm i @material-ui/core
```
```bash
npm install @mui/icons-material
```
```bash
npm i navigate
```
```bash
npm i bootstrap
```

## Installation guide:

En utilisant graddle: 

- clean
- assemble
- test. ***Tous les tests doivent passer***
- Lancer server docker