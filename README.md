## Install nodemon

```
$ npm i nodemon --save-dev
```

## Install Convert CSV to JSON

```
$ npm i convert-csv-to-json
```

## Install graphql & apollo-server

```
$ npm i graphql apollo-server
```

## Run DBTester as nodemon

```
$ npm i
$ nodemon dbtester.js
```

## Connect to Apollo Server
http://localhost:4000

### Query
```json
query {
  equipments {
    id
    used_by
    count

  }

}

```