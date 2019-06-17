# Projet 3 Simulateur Loi Pinel
Development of a business application for real estate managers for a Pinel Law simulator.

### Prerequisites

You need [Composer](https://getcomposer.org/download/) and [Yarn](https://yarnpkg.com/fr/docs/install#debian-stable) in your computer.

### Installing

* Clone the project `git clone https://github.com/GamerPsy/WCS_Projet3_SimulateurLoiPinel.git`
* Open the folder, configure the constants in *.env* file 
```
APP_ENV=dev
APP_SECRET=your-secret-message
DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name
MAILER_URL=null://localhost
```
* Run commands
```
composer install
yarn install
yarn encore dev
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
php bin/console doctrine:fixtures:load
```
* Create an user admin
`php bin/console app:create-user <email> <password> <society>`
* Run server `php bin/console server:run`

### Build With
* HTML 5
* CSS 3
* Bootstrap 4
* JS / jQuery
* PHP 7
* Symfony 4
* Twig
* Doctrine

### Versioning

* Git

### Project management

* Scrum / Agile
* Git Workflow
 
### Contributors

* Anthony JONAS - [accuratecopy](https://github.com/accuratecopy)
* Christophe LESIEUR - [chrlesieur](https://github.com/chrlesieur)
* Thomas COUMES - [ThomasCoumes](https://github.com/ThomasCoumes)
* Jovanéla DARIBO - [carly97232](https://github.com/carly97232)
* Rémy DUCRY- [GamerPsy](https://github.com/GamerPsy)

###### Duration of the project : 8 weeks
