# Dj Equipments

I created this fake api for djs and developers who wants to find information about dj equipments.

You can modify or add new products

## NPM

```bash
npm install
```

## How to call json server?

```bash
npm run json:server
```

## How to call equipments from Fake REST API

```bash
Get Single Products
http://localhost:3000/players/1
http://localhost:3000/mixers/10
http://localhost:3000/controllers/19
http://localhost:3000/turntables/33

Filter By Name
http://localhost:3000/players?name=CDJ-2000NXS2

Pagination & Limit
http://localhost:3000/players?_page=1&_limit=2

Sorting
http://localhost:3000/players?_sort=name&_order=asc

Range
http://localhost:3000/turntables?id=34

Text Search
http://localhost:3000/players?q=MPEG
```
