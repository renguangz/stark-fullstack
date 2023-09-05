# Stark Pretest

* 執行前後端
```
$ docker-compose build
$ docker-compose up -d
```


* Backend: http://localhost:3000
* Backend Swagger: http://localhost:3000/api
* Frontend: http://localhost:4200

* 分頁功能，目前沒有實作，如果要實作的話，會在 `/todos` 後面帶 query page_at, page_size (`/todos?page_at=1&page_size=10`)。前端透過 setQueryParams call api
