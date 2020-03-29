<div align="center">
  <img src="./img-readme/logo.svg" alt="Be The Hero"><br>
  <a href="https://github.com/ricassiocosta/BeTheHero-api/blob/master/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/ricassiocosta/bethehero-api?color=E02041"></a>
</div>
# Be The Hero - backend<br>
Be The Hero is an application in which NGOs can register cases to collect donations.
Created at Semana OmniStack 11.0 by <strong>Rocketseat</strong>

## About

The backend of this application was created using Nodejs and some libraries of route configurations, database and access control.

### Here is the list of used libraries and their main features.
<ul>
  <li><strong>Cors</strong>: CORS gives web servers the ability to tell when they want to choose to allow access to their resources between origins.</li>
  <li><strong>Express</strong>: Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.</li>
  <li><strong>Knex</strong>: Knex.js is a "batteries included" SQL query builder for Postgres, MSSQL, MySQL, MariaDB, SQLite3, Oracle, and Amazon Redshift designed to be flexible, portable, and fun to use.</li>
</ul>

The database chosen to be used in the backend was SQLite, which is fully implemented using a SQL Query Builder, which in this case was Knex, which allows us to perform all database maintenance operations using javascript.

If you want to test the application on your machine, just perform a 'clone' of this repository, or simply download both this repository, as well as the <a href="https://github.com/ricassiocosta/BeTheHero-frontend/">frontend</a> and <a href="https://github.com/ricassiocosta/BeTheHero-mobile/">mobile</a> repositories. Then just run the following codes:

<strong>yarn install</strong>
then
<strong>yarn start</strong>
