AllPositions API Client
=======================

Client for [AllPositions API](http://allpositions.ru/help/api/)
    
Installation
------------

### Via [composer](https://getcomposer.org/)

Run this:

```
composer require ursaevandrey/allpositions
```

or add to the require section of your composer.json

```json
"ursaevandrey/allpositions": "~1.0.0"
```

Usage
-----

```
$allpositions_client = new allpositions\api\Client(API_KEY);
$projects = $allpositions_client->getProjects();

var_dump($projects);
```