## Welcome to Getintent PHP developer test

What we going to test here:

* Your architect skills
* Knowledge of PHP programming language
* Knowledge of Symfony/Laravel
* Knowledge of database structures


## Test description

---

Background:

* You need to use Symfony/Laravel framework
* Use any tools or libs for test completion
* You need to use database (MySql/PostgreSQL)

## Description

Build REST API service that provides weather forecast from 
some provider. You must use authentication for api endpoints.
Use your preferred hosting provider for demo.

### API Spec

```
GET /forecast/current?city=(string) - current weather forecast
GET /forecast/tomorrow?city=(string) - weather forecast for tomorrow
GET /cities - list of available cities for weathe forecast. Must use streamable design
```

### Details

1. Write Cron job command that will gather forecast data and will 
   store that data in database. 
2. Use interface for forecast fetching service (in future we can chage provider)
3. Define some authentication entity (token,user) and allow only that users to 
   interfere with API
4. Use HTTP [caching][http-caching]
5. Write tests

_If you have any questions, please write an [email][email]_


[http-caching]: https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching
[email]: mailto:andrew.lykov@yandex.ru