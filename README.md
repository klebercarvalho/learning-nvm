# learning-nvm
Learn NVM

MVM

[https://github.com/creationix/nvm](https://github.com/creationix/nvm)

nvm version
```sh
$ nvm --version
```

nvm help
```sh
$ nvm --help
```

List installed versions
```sh
$ nvm ls
```


List remote versions available for install
```sh
$ nvm ls-remote
```


Display currently activated version

```sh
$ nvm current
```

When listing, only show LTS (long-term support) version

```sh
$ nvm ls-remote --lts
```

Install a specific version number

```sh
$ nvm install 8.0.0                     
```

Use the latest available 8.0.x release

```sh
$ nvm use 8.0  
```

Run app.js using node 6.10.3

```sh
$ nvm run 6.10.3 app.js 
```

Uninstall a version

```sh
$ nvm uninstall <version>
```
