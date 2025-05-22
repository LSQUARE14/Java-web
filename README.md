# 👔 Clothing E-Commerce System

This repository is made by me and my fellows to relearn coding practices and get some co-working experiences. 

Contributors:
- `LSQUARE14`
- `Ld4vicl`

## 1. Techstack:

### Front-end:
- HTML
- CSS
- JS and its libraries.
- Tailwind.
### Back-end:
- **Server**: PHP
- **Database**: MySQL
- **Others**: Docker, Github, CI/CD.
## 2. Rules for contributors:

- Apply OOP.
- Maintain organized folder structure and clean architecture for scalable purpose (recommendation: MVC or HMVC).
- Having RBAC for access management control.
- Naming class, functions, variables, constants with **Pascal Case**.
- Language: English.
- **NO AI ALLOWED**.

## 3. Folder structure: 

Currently, this repo using HMVC folder structure like this:
- `config`: contains custom PHP config files.
- `css`: contains the project's CSS files.
- `helpers`: contains 'helpers' files (each file is a collection of related functions).
- `images`: contains the project's images.
- `js`:  contains the project's Javascript files.
- `lib`:  contains PHP classes specific to the project.
- `modules`:  My HMVC framework that packing each ***features*** as a module that contains, for example:
    - **UserAuthorization** - An example module
        - *controllers* - contains the controllers for this module.
        - *models* - contains the models for this module.
        - *views* - contains the views for this module.
- `views`: contains views that should be globally accessible (page header, footer, etc).
- `build`: for Dockerfile, docker-compose.yaml and custom build script for building purpose.

## 4. Resources:

| Name | Description | References |
|---|---|---|
| PHP Folder Structure with HMVC Framework | For applying well organized folder structure  | https://stackoverflow.com/questions/1387547/what-is-the-most-scalable-php-based-directory-structure-for-a-large-site |
| Docker Documentation (For Dockerfile)   | This reference provide basic syntax and rules for writing Dockerfile | https://docs.docker.com/get-started/docker-concepts/building-images/writing-a-dockerfile/ |


