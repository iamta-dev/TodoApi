# TodoApi

## ref: https://docs.microsoft.com/en-us/learn/modules/build-web-api-aspnet-core/1-introduction

# start app
```
$ dotnet run
```

# get api
```
$ httprepl http://localhost:5000
(Disconnected)> connect http://localhost:5000
$ cd Pizza && ls
$ post -c "{"name":"Hawaii", "isGlutenFree":false}"
$ get
$ get 3
$ put 3 -c  "{"id": 3, "name":"Hawaiian", "isGlutenFree":false}"
$ delete 3
```

$ Docker
```
$ docker run -p 8000:80 -d tazgg/todo-api
$ curl http://localhost:8000/Pizza/1
```
