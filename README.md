# Hahn applicatonProcess application

## Frontend built With

- [Aurelia](http://aurelia.io/docs/tutorials/creating-a-todo-app#setup) - The web framework used
- [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/download) - UI library

## Backend built With

- [NetCore](https://docs.microsoft.com/en-us/dotnet/) - The webapi framework used

### Server

### Installing App

Get git source code :

```sh
$ git clone https://github.com/ronnysuero/Hahn.ApplicatonProcess.Application.git
```

 docker image :

```sh
$ cd Hahn.ApplicatonProcess.Application
$ docker build -t hahnapplicatonprocessfebruary2021web -f Hahn.ApplicatonProcess.February2021.Web/Dockerfile .
$ docker run --rm -d  -p 5000:5000/tcp hahnapplicatonprocessfebruary2021web
```

Go to the browser: `http://localhost:5000/` and that's it.

## Author

Ronny Zapata – ronnysuero@gmail.com

## License

This software is licensed under the [MIT](https://github.com/nhn/tui.editor/blob/master/LICENSE) ©